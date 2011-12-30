source "http://rubygems.org"

group :development do
  gem 'rspec-expectations'
  gem 'rspec-mocks'
  gem 'rspec-core'
  gem 'guard', "0.8.8"
  gem 'libnotify'
  gem 'rb-inotify'
  # Vagrant dev / tests started out as testunit, and still uses test/unit/* as the path
  # however the continued use of *_test.rb causes problems for guard.
  # Using my one line patch to guard-rspec monkey patches the problem.
  # A better solution can probably be found.
  gem 'guard-rspec',
    :git => "git@github.com:hh/guard-rspec.git",
    :branch => "feature/vagrant_not_standard"
end
