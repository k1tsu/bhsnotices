
source "https://rubygems.org"

gem "utopia", "~> 2.5.5"
# gem "utopia-gallery"
# gem "utopia-analytics"

gem "rake"
gem "bundler"

gem "file-utils"

gem "rack-freeze", "~> 1.2"

group :development do
	# For `rake server`:
	gem "guard-falcon", require: false
	gem 'guard-rspec', require: false

	# For `rake console`:
	gem "pry"
	gem "rack-test"

	# For `rspec` testing:
	gem "rspec"
	gem "covered"
end

group :production do
	# Used for passenger-config to restart server after deployment:
	gem "passenger"
end
