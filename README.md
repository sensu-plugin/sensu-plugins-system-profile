## Sensu-Plugins-system-profile

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-system-profile.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-system-profile)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-system-profile.svg)](http://badge.fury.io/rb/sensu-plugins-system-profile)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-system-profile/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-system-profile)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-system-profile/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-system-profile)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-system-profile.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-system-profile)

## Functionality

## Files
 * bin/extension-system-profile

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-system-profile -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-system-profile`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-system-profile' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-system-profile' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
