
#nice-css3-hmenu
*A UI fragment that exploits CSS3 3D capabilities on a horizontal menu*

In my quest of extracting UI fragments from inspiring web apps (and the possibility to reuse it later), here is the second item on the serie (please see [nice-boot-sidebar](https://github.com/FranckyU/nice-boot-sidebar) which began the serie)

## What it looks like ?

Here's the [link to the result on JSFiddle](http://jsfiddle.net/4V8ee/3/) 
Or better, [here you can view it full screen](http://jsfiddle.net/4V8ee/3/embedded/result/)

## Usage

The complete template is built with [Stasis](https://stasis.me) using my base template for front-end prototyping [StasisTPL](https://github.com/FranckyU/StasisTPL.git) so you should have a valid Ruby environment to run it, I use RVM.

CSS are written with [SASS](http://sass-lang.com)
HTML are written with [HAML](http://haml.info)

To run the example, just do

```bash
git clone https://github.com/FranckyU/nice-css3-hmenu.git
cd nice-css3-hmenu
bundle #assuming you already have a ruby environment
stasis -d 3000

# Now you should have it visible at http://127.0.0.1:3000
```

For non Ruby-Stasis users, just copy the compiled HTML structure in `index.html` along with JS, CSS and image files from `/public` folder into your project and that should be OK.


---

## Changelog
*2013-12-03*
- First commit