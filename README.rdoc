# Fluent::Plugin::Redis::Publish

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'fluent-plugin-redis-publish'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fluent-plugin-redis-publish

## Usage
channel name is same as tag,bellow use 'log' as tag


<match log>
  type redis_publish
  host 10.15.201.180
  port 6379
</match>

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
