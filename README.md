# Content First Prototyping Project Base
This is a bare bones project base for the Content First Prototyping framework. If this is the first page you’ve visited about content first prototyping, be sure to also check out the [Smashing Magazine article](https://www.smashingmagazine.com/2016/05/content-first-prototyping/) that introduces the framework, or the [Content First Prototyping Starter Kit](https://github.com/andybywire/content-first-prototyping) repository, which has a wider selection of patterns, pages, and templates.


## Dependencies

- [Command line tools](http://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/)
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (if you’re on a Mac, this is probably already installed)
- [Node.js](https://nodejs.org/en/)
- [Bower](https://bower.io/#install-bower)

## Installation

1. Install the Jekyll gem and Gulp (use `sudo` if you see permission errors)

        $ gem install jekyll

    NB: If you get the error:

        ERROR:  While executing gem ... (Errno::EPERM)
          Operation not permitted - /usr/bin/listen

    this is because /usr/bin is [“off-limits” since El Capitan](http://stackoverflow.com/questions/31972968/cant-install-gems-on-os-x-el-capitan). If you run into this, [try instead](https://github.com/sass/sass/issues/1768):

        $ sudo gem install -n /usr/local/bin jekyll

    Thanks to [thamrick](https://github.com/thamrick) for finding the fix!

2. Clone/copy the Content first Prototyping Starter Kit to your project folder (this will take a minute or so)

        $ git clone https://github.com/andybywire/cfp-framework.git <name_of_project>

    **- or -**

    Download and copy the [.zip](https://github.com/andybywire/cfp-framework/archive/master.zip) 

3. Navigate to your project file and install the framework dependencies

        $ cd <path to your project folder>

        $ bower install

        $ npm install

4. Run `gulp`. Once installed, this is the only command you'll need to run to begin a new session. 

        $ gulp

## Documentation

In order to get the most out of the framework, it's worth familiarizing yourself with the basics of the tools it's built with. The documentation of all of these tools is excellent and should get you up to speed quickly:

- [Jekyll](http://jekyllrb.com/docs/home/)
- [The Jekyll Data Pages Generator plugin](https://github.com/avillafiorita/jekyll-datapage_gen)
- [Foundation](http://foundation.zurb.com/sites/docs/kitchen-sink.html)
- [Markdown syntax](https://daringfireball.net/projects/markdown/syntax)

If you need more detail on getting started with the Framework itself, check out the [Content First Prototyping Starter Kit](https://github.com/andybywire/content-first-prototyping.git). 
