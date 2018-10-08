source "https://rubygems.org"
git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem "bundler", ">= 1.8.4"

gem "pg", :require => "pg"
gem "rails", "~> 4.2.10"

gem "excon"
gem "aasm"
gem "active_model_serializers"
gem "acts-as-taggable-on"
gem "app"
gem "bitbucket_rest_api", :github => "renderedtext/bitbucket"
gem "bunny"
gem "dalli"
gem "devise"
gem "dynamic_form"
gem "faraday"
gem "friendly_id"
gem "grpc"
gem "httparty"
gem "httpclient"
gem "json"
gem "kaminari"
gem "local_time"
gem "lograge"
gem "net-ssh" # Used for generating private key fingerprint(Adds the fingerprint method to the OpenSSL::PKey::PKey class)
gem "newrelic_rpm"
gem "octokit"
gem "omniauth-bitbucket"
gem "omniauth-github"
gem "multi_logger"
gem "redlock"
gem "retryable"
gem "sentry-raven"
gem "sidekiq", "< 6"
gem "sidetiq"
gem "simple_oauth"
gem "sshkey"
gem "strongbox"
gem "puma"
gem "xmlrpc" # Prior to ruby 2.4 this was bundled with ruby. Required by active-support.

gem "rt-watchman", :require => "watchman"
gem "rt-logman", :require => "logman"
gem "rt-tackle", :require => "tackle"

group :development do
  gem "spring"
  gem "spring-commands-rspec"
end

group :test, :development do
  gem "awesome_print"
  gem "bullet"
  gem "pry-byebug"
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "rspec-benchmark"
  gem "rspec-its"
  gem "rspec-rails"
  gem "rubocop"
  gem "rubocop-rspec"
  gem "test-unit"
  gem "thin"
  gem "timecop"
  gem "grpc-tools"
  gem "dotenv-rails"
end

group :test do
  gem "selenium-webdriver", "~> 2.53"
  gem "shoulda"
  gem "show_me_the_cookies"
  gem "vcr"
  gem "webmock"
end
