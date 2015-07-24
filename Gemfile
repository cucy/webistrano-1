if RUBY_VERSION =~ /1.9/ # assuming you're running Ruby ~1.9
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end
source "http://rubygems.org"

gem "rails", "=2.3.14"
gem "composite_primary_keys", "~> 2.3.5.1"
gem "erubis"
gem "mysql"
gem "rake"
gem "rdoc"
gem "syntax"
#gem "capistrano", "~> 2.13.4"
gem 'capistrano', "~> 2.15"
gem "net-ssh", "~> 2.7.0"
gem "open4"
gem "version_fu"
gem "exception_notification", "2.3.3.0"
gem "thin"
gem 'capistrano_rsync_with_remote_cache', :git => 'git://github.com/jverdeyen/capistrano_rsync_with_remote_cache.git'
gem "colored"
gem "unicorn"

group :test do
  gem "mocha", "0.9.8"
end
