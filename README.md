# http-response-pages
Standard HTTP response pages, that can be rendered with the appropriate status in Ruby on Rails

Code for rendering these templates:

```ruby
render(:file => File.join(Rails.root, 'public/403.html'), :status => 403, :layout => false)
```

Replace 403 with any of the following supported templates.

### Currently supported templates :-

- 200
- 201
- 403
- 404
- 422
- 500

HTML files licensed under MIT.

Copyright [Siddharth Kannan](http://github.com/icyflame) 2015
