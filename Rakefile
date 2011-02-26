require_relative 'devel/jumpstart'

Jumpstart.new "live_ast_ruby_parser" do |s|
  s.camel_name = "LiveASTRubyParser"
  s.developers << ["James M. Lawrence", "quixoticsycophant@gmail.com"]
  s.github_user = "quix"
  s.description = s.summary
  s.dependencies = [
    #
    # my code compensates for a ruby_parser bug; make this equal for now
    #
    ["ruby_parser", "= 2.0.6"],
    ["ruby2ruby", ">= 0"],
  ]
end

task :test do
  puts "Testing is done with the LiveAST test suite."
end

task :default => :test
