source "https://rubygems.org"

ruby "2.6.6"

gem "jets", "~> 2.3.16"

gem 'haml-jets', "~> 0.1.1"
gem "jetpacker", "~> 0.4.2"
gem "pg", "~> 1.1.3"

# development and test groups are not bundled as part of the deployment
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'shotgun'
  gem 'rack'
  gem 'puma'
end

group :development do
  gem 'foreman', "~> 0.87.1"
end

group :test do
  gem 'rspec' # rspec test group only or we get the "irb: warn: can't alias context from irb_context warning" when starting jets console
  gem 'launchy'
  gem 'capybara'
end
