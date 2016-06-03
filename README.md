# ActiveMerchant PaypalBogusGateway

Gateway used for testing Paypal integration via ActiveMerchant,
[extracted from old Pull Request](https://github.com/activemerchant/active_merchant/pull/424)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'active_merchant-paypal-bogus-gateway'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install active_merchant-paypal-bogus-gateway

## Usage

Load the extension in you tests which need it

```ruby
require "active_merchant-paypal-bogus-gateway/ext/paypal\_bogus\_gateway"

ActiveMerchant::Billing::PaypalBogusGateway.new
```

For more details checkout
[this post](https://web.archive.org/web/20150211210445/http://infotrope.net/2013/05/31/testing-paypal-express-with-activemerchants-bogusgateway-and-how-to-make-it-work)

## Development

Run `bundle install` to get all the needed dependecies and `bundle exec rake` to run the tests.

## Contributing

Create a bug report and / or pull request!


