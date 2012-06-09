# bakeo500

- Reminder bot
    - Using twitter

# Components
- ruby
- heroku
- heroku scheduler addon
- twitter gem

# Install
```
$ gem install bundler --pre
$ heroku apps:create YOUR_APP_NAME --stack cedar
$ bundle
```

# Set up
- [ddollar/heroku-config](https://github.com/ddollar/heroku-config)
- [My applications | Twitter Developers](https://dev.twitter.com/apps)
- Edit limit time in bin/within-the-limits
- Edit status for twitter in bin/sorry-i-forget

# Wake up
```
$ git push heroku master
$ ./bin/bakeo-wake-up
  => Register heroku scheduler addon
  => Add command and set scheduler manually

```

# Snooze
```
$ ./bin/bakeo-snooze
  => Remove heroku scheduler addon
```

# This is for
- 1hour contest

# License
- MIT License
- sanemat
