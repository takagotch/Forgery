### Forgery
---
https://github.com/sevenwire/forgery

```ruby
Forgery(:basic).password
Forgery(:internet).email_address
Forgery(:monetary).money
Forgery(:lorem_ipsum).words(10)
Forgery(:monetary).formatted_money :min => 100, :max => 1000

Forgery::Basic.hex_color
Forgery::Name.full_name
Forgery::Personal.shirt_size


```

```
gem install forgery
gem 'forgery', '0.6.0'

bundle exec
rails g forgery

```



```
```


