## Sensu-Plugins-conntrack

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-conntrack.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-conntrack)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-conntrack.svg)](http://badge.fury.io/rb/sensu-plugins-conntrack)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-conntrack/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-conntrack)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-conntrack/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-conntrack)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-conntrack.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-conntrack)

## Functionality

## Files
 * bin/metrics-conntrack

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-conntrack -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-conntrack`

#### Bundler

Add *sensu-plugins-contrack* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-conntrack' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-conntrack' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
