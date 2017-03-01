# Resume Readme

This repository contains my resume, in a simple, version-controlled format. The raw content is available in [markdown](resume.md). The goal of this repo is to make it really simple and easy to update, as well as handily convertible into a variety of other formats for distribution with minimal effort.

[Jekyll](https://jekyllrb.com) is used to transform it into a web format using a custom template I made specifically for this resume, and is automagically hosted by Github, which you can view live at [dbburgess.github.io/resume](https://dbburgess.github.io/resume). I've also provided it in [PDF format](resume.pdf) in this repository for convenience.

## Running Web Version Locally

If you want to run the web version locally, you'll need [Jekyll](https://jekyllrb.com) installed.

Simply run `jekyll serve`, and then open your web browser to [http://127.0.0.1:4000](http://127.0.0.1:4000).

## PDFizing The Resume

There are numerous approaches to automating this, such as using [wkhtmltopdf](http://wkhtmltopdf.org) or [PhantomJS](http://phantomjs.org). Ultimately, I couldn't find an automated solution that rendered satisfactorily. The crux of the issue in most of the tools I tried seems to be the CSS property `column-count`, which I'm using to increase information density and improve organization in several sections. I could adjust the design, but I'm rather happy with it and don't think that's worth it at this point. Both projects have open issues you can track ([wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf/issues/2266), [PhantomJS](https://github.com/ariya/phantomjs/issues/11821)).

I've yet to find a simple, viable workaround. However, it's rather easy to do manually:

* Run the web version locally using Jekyll.
* View in Chrome.
* Print to PDF.

Of course, I'd much rather it be automated, but at least it's pretty quick and easy. The output of those steps looks significantly better than anything else I've found, so I'm sticking with it for the time being until a better solution is identified. If you have any ideas, please do let me know!

## License / Usage

You are welcome to use this as a base to build off of for your own resume. However, I have a few simple requests:

* You must use your own content instead of pretending to be me. I know I'm pretty awesome, but you're probably awesome in your own unique way, too. So be you, [not me](http://i.imgur.com/5UvJcf9.gif). :)
* I'd prefer if you came up with your own style / design (aka the html / css) since I put a lot of effort into making mine unique. If you just copy mine, you're taking that away from me. :(
* If you found this helpful in any way, I'd love to know! Open an issue, shoot me an email, whatever floats your boat! It'd make my day to hear from you.
* If you put up a repo with your own remix of this, it'd be spectacular if you gave me a shoutout, although it isn't required (but I'd still love to see what you did).

