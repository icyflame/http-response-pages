# http-response-pages
Standard HTTP response pages, that can be rendered with the appropriate status in Ruby on Rails

Code for rendering these templates:

```ruby
render(:file => File.join(Rails.root, 'public/403.html'), :status => 403, :layout => false)
```

Replace 403 with any of the following supported templates.

### Currently supported templates :-

- [200](http://icyflame.github.io/http-response-pages/200.html)
- [201](http://icyflame.github.io/http-response-pages/201.html)
- [403](http://icyflame.github.io/http-response-pages/403.html)
- [404](http://icyflame.github.io/http-response-pages/404.html)
- [422](http://icyflame.github.io/http-response-pages/422.html)
- [500](http://icyflame.github.io/http-response-pages/500.html)

HTML files licensed under MIT.

Copyright [Siddharth Kannan](http://github.com/icyflame) 2015
