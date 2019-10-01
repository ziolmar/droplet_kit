source 'https://rubygems.org'

gem 'simplecov'
# Specify your gem's dependencies in droplet_kit.gemspec
gemspec

version = case (ENV['ACTIVESUPPORT_VERSION'] || '6')
          when '6'
            '~> 6.0'
          when '5'
            '>= 5.0.0.beta3'
          when '4'
            '~> 4.0'
          when '3'
            '~> 3.1'
          end
gem 'activesupport', version
