task :default => :test

desc "Run bin/rps_main.rb"
task :bin do
	sh "ruby -Ilib -Ispec bin/rps_main.rb"
end

desc "Run tests with --format documentation"
task :test do
	sh "rspec -Ilib spec/ppt_spec.rb --format documentation"
end

desc "Run tests with format: html"
task :html do
	sh "rspec -Ilib spec/ppt_spec.rb --format html"
end