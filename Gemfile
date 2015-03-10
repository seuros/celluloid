source 'https://rubygems.org'
gemspec development_group: :gem_build_tools

gem 'coveralls', require: false
gem 'pry'

gem 'timers', github: 'celluloid/timers'

if RUBY_PLATFORM =~ /darwin/
  gem 'rb-fsevent', '~> 0.9.1'
end

group :development do
  gem 'rspec', '~> 2.14.1'
  gem 'guard-rspec'
  gem 'benchmark_suite'
  gem 'rubocop'
end

group :gem_build_tools do
  gem 'rake'
end
