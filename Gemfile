source "http://rubygems.org"

gem 'rails', :path => File.expand_path("../vendor/rails", __FILE__)

%w[rspec rspec-core rspec-expectations rspec-mocks rspec-rails].each do |lib|
  gem lib, :path => File.expand_path("../../#{lib}", __FILE__)
end

gem 'sqlite3-ruby', :require => 'sqlite3'

gem "cucumber", "0.8.5"
gem "aruba", "0.2.2"
gem 'webrat', ">= 0.7.2"
gem 'autotest'
gem 'relish'

case RUBY_VERSION
when /^1\.9/
  gem 'ruby-debug19'
when /^1\.8/
  gem 'ruby-debug'
end
