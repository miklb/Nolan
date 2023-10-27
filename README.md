# Nolan

[Kubrick](https://wordpress.org/themes/default/) was my first exposure to developing for the web. As a nod to that, I've chosen another director to name this project after. (Naming things is hard.)

The goal of this project is to be a genuinely minimalistic blog built with [Eleventy](https://www.11ty.dev/) with support for [CloudCannon](https://cloudcannon.com/). 

## 1.0 Milestone

Goals:
* full microformats2 support for:
  * Articles
  * Notes
  * Photos
* post and successfully syndicate through brid.gy to:
    * Mastodon
    * Bluesky
* send and receive webmentions using webmentions.io

## About the markup
As stated, the attempt is to be minimal in both design and markup. Focus is on responsiveness and readability. See also accessibility.

I utilze PostCSS (probably not as well as I should) to compile the CSS. Primarily I use it for including files and smushing it all together but it does run through preset-env. Room for improvement here. I've looked long and hard at ways folks organize their CSS and for a blog one file could probably be fine but I like to separate them by function. I haven't run into any specificity issues with how I'm compiling them but again, it's a minimalist blog. Your milage may vary.

## License

Do whatcha like.

## Post Script

I've been building and thinking about how blogs are built for almsot two decades. I'm excited about the renaissance of sorts in blogging and the disruption of the social media landscape. If not always a follower, I've always been a beleiver in the principals of the IndieWeb. This project will be my attempt to take all of the lessons and perspectives I've encountered along the way and build something that I hope helps more folks get on board with the IndieWeb.

