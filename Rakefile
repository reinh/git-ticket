require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "git-ticket"
    gem.summary = %Q{Checkout, create, delete or list ticket branches}
    gem.description = gem.summary
    gem.email = "reinh@reinh.com"
    gem.homepage = "http://github.com/reinh/git-ticket"
    gem.authors = ["Rein Henrichs"]
    gem.add_dependency 'commandant'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default => :build
