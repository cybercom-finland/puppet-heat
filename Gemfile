source 'https://rubygems.org'

group :development, :test do
  gem 'puppetlabs_spec_helper', :require => false
  gem 'puppet-lint', '~> 1.1'
  gem 'rspec-puppet', '~> 1.0.1'
  gem 'puppet-lint-param-docs', '1.1.0'
  gem 'rake', '10.1.1'
  gem 'rspec', '< 2.99'
  gem 'json'
  gem 'webmock'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
