# Notebook
### My notes, available and open to contributions

# Static requirements optimisations
This builds upon modern.html
meta tags. leav in  minimal ui 
http://absolide.tumblr.com/post/100022548384/the-minimal-ui-is-dead-long-live-the-minimal-ui

Should have a robots.txt



# Managing a website

# Improving website performance

### Images as a service
http://confreaks.tv/videos/rubyconf2015-your-own-images-as-a-service

### Reducing HTTP requests.
**Web fonts** are an external request that cannot be inlined. This [article](http://bdadam.com/blog/loading-webfonts-with-high-performance.html) gives advice for high performance loading of webfonts

# Business
### Getting work
Guide to hiring a ruby developer explains ruby vs rails, can share
https://gun.io/blog/hackers-guide-to-hiring-a-ruby-on-rails-developer/?utm_source=rubyweekly&utm_medium=email

### Discovery process
The discovery process is expanding the process of scoping so that clients have an actionable out put regardless of wether they carry on with us or not

https://gun.io/blog/charging-for-discovery-process/



# Things without a section so far

## Offline resources
http://jakearchibald.com/2014/offline-cookbook/#on-install-as-a-dependency
https://github.com/jakearchibald/offline-wikipedia/blob/master/index.js
https://github.com/filamentgroup/loadCSS/issues

## List of services to pair with static sites
This is a good list of services as it stands at the moment. Will have to review as I use them
http://cloudcannon.com/tips/2014/12/12/the-ultimate-list-of-services-for-static-websites.html

- I like Stripe
- I think UserApp no longer exists
- Forms I would build myself
- MailerLite fine so far slightly low features but perhaps worth it for price


## File upload without carrier wave
https://www.codefellows.org/blog/tutorial-how-to-upload-files-using-the-aws-sdk-gem
I think this would be worth exploring further in conjunction with errol

## Arguments for a github based work flow
http://blog.codeship.com/five-suggestions-for-building-an-infrastructure-for-innovation/

https://guides.github.com/introduction/flow/

## Browser quirks
probably going to be a large section

on iphone to make something fire a click event when tapped give it a pointer cursor
```css
.clickable-div {
    cursor: pointer;
  }
```
https://stackoverflow.com/questions/3705937/document-click-not-working-correctly-on-iphone-jquery/17490775#17490775

on iphone to prevent scrolling after making a page 100%
```css
body {
  # for iphone 
  position: fixed;
  # for windows phone
   -ms-touch-action:none;
}

## jekyll
rediret after renaming a blog post
https://help.github.com/articles/redirects-on-github-pages/


http://calendar.perfplanet.com/2013/slow-pages-damage-perception/

handling security
https://www.youtube.com/watch?v=9WuP4KcDBpI

## talks resources and people
- [97 things every programmer should know](http://programmer.97things.oreilly.com/wiki/index.php/97_Things_Every_Programmer_Should_Know)
- [Epigrams on Programming](https://en.wikipedia.org/wiki/Epigrams_on_Programming)
- [Power use of Value in DDD](http://www.infoq.com/presentations/Value-Objects-Dan-Bergh-Johnsson)
