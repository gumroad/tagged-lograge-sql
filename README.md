## Installation

Add this line to your application's Gemfile:

```ruby
gem 'tagged-lograge-sql'
```

## Usage

In order to enable SQL logging in your application, you'll simply need to add this on top of your lograge initializer:

```ruby
# config/initializers/lograge
require 'lograge/sql/extension'
```
