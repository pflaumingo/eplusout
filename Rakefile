require "rake/testtask"

Rake::TestTask.new do |t|
  t.libs << "unit"
  t.test_files = FileList["test/**/*_spec.rb"]
  t.verbose = true
end

task :default => :test