This app is an example app for an [issue with sprockets](https://github.com/rails/sprockets/issues/183).

## Instructions

- Start server and go to root URL.
- Remove `coffee-rails` from Gemfile.
- Remove `app/assets/javascripts/file.coffee`.
- Restart server and go to root URL.
- You should see "cannot load such file -- coffee_script".
- Run `rake tmp:cache:clear` and go to root URL.
- No error this time.
