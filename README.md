# Ruboty::Trello

Ruboty plugin for adding a new card to Trello.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ruboty-trello'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ruboty-trello

## Usage

```
@ruboty trello b <board_name> l <list_name> (lb <label_name>) c <card_name>
```

## ENV

### required

```
TRELLO_DEVELOPER_PUBLIC_KEY - Developer API Key
TRELLO_MEMBER_TOKEN - Member Token (require read&write scope)
```

see https://github.com/jeremytregunna/ruby-trello#configuration to get these keys

### optional

```
TRELLO_AUTO_ASSIGN - If set to '1', assigns sender with created card
TRELLO_RESPONSE_PREFIX - Specify response message (default is 'Created')
```

## Contributing

1. Fork it ( https://github.com/bitjourney/ruboty-trello/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
