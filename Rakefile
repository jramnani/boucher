require 'rubygems'
require 'rspec/core/rake_task'

desc "Run unit specs"
RSpec::Core::RakeTask.new do |t|
  t.pattern = "./spec/**/*_spec.rb"
end

desc "Default: run the specs."
task :default => :spec
