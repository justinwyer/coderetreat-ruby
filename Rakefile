require 'rake/testtask'

Rake::TestTask.new :test do |t|
  t.libs.push "lib"
  t.test_files = FileList['test/test_*.rb']
  t.verbose = true
end

Rake::TestTask.new :spec do |t|
  t.libs.push "lib"
  t.test_files = FileList['specs/*_spec.rb']
  t.verbose = true
end