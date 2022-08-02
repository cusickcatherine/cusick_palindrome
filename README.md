# Palindrome Detector

`cusick_palindrome` is a sample Ruby gem, modeled off Michael Hartl's gem in [Learn Enough Ruby to be Dangerous](https://www.learnenough.com/ruby).

## Installation

To install `cusick_palindrome`, add this line to your application's `Gemfile`:

```ruby
gem 'cusick_palindrome'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install cusick_palindrome

## Usage

`cusick_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'cusick_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true
```
