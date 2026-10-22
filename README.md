# Blog Website

A static blog about web programming languages, made in September 2020 as the final project for a "monitoring technological development" college course. Built by Mihir Rathod and me.

We started from Webflow's free "Moon" blog template, downloaded it with HTTrack, and then edited the HTML by hand to add our own content.

## What's in it

- A home page listing five posts: ASP.NET, Angular, Go, Ruby and Rust
- One page per language with a short intro, history, and a "Differences" section comparing it with other languages and frameworks (for example Go vs Python, Rust vs Java, Ruby vs Ruby on Rails). The comparisons are images in `moon-template.webflow.io/img/`
- About and Contact pages

The site is plain HTML and CSS, plus the Webflow, jQuery 2.2.0 and WebFont loader scripts that HTTrack saved locally.

## Viewing it

There's no build step. Open `moon-template.webflow.io/index.html` in a browser. The root `index.html` is the HTTrack index page, which links to the same place.

## Notes

- Everything outside `moon-template.webflow.io/` (`hts-cache/`, `hts-log.txt`, `cookies.txt`, `.vs/`, `debug.log`) is leftover from HTTrack or Visual Studio and isn't part of the site.
- The contact form is the Webflow one and has no backend here, so it doesn't send anything.
- Some links from the original template (`all-posts.html`, an unused sample post) weren't downloaded and are broken. Parts of the post pages still have the template's placeholder text below our content.
- The post pages reference images as `.png` while most files are saved as `.PNG`. That works on Windows and macOS but the images won't load from a case-sensitive server.
