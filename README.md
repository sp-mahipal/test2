# Photography
A jekyll website for photographer cum developer

## Quick Start
If you're a developer and love taking pictures then this open-source project may help you setup a website to showcase
all your creations without effort. And not just that, with this you need not pay a single dime to host your website as
it's hosted by GitHub for FREE.

**Just follow the below steps and your website would be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable github pages from the repo settings.
3. Upload your pictures to `images/fulls` and `images/thumbs` directory. _You can do that on github.com itself or you can clone and push the images to your repo._
4. Add your own custom domain in `CNAME` file or just remove the file if you don't own a domain. _You can use the default domain that github provides._
5. And that's it, your website is set. To view, go to [photography.ramswaroop.me](http://photography.ramswaroop.me) (or whatever you have in the CNAME file) and if you don't have one, you can go to [yourusername.github.io/photography](http://yourusername.github.io/photography)
 
## ProTips
I have made this as an [npm](https://www.npmjs.com) package with [gulp](http://gulpjs.com/) to automate my image resizing and thumbnail generation. So if you're lazy 
like me then you can just do the following before you push your images to github.

1. Go inside the project `$ cd photography`
2. Install all dependencies by `$ npm install`
3. Copy all your pictures (the largest size available, straight from your camera) and put it inside `images/fulls` directory
4. `$ gulp` to resize the images and to generate thumbnails for faster page loads
5. Push your changes to github.com by `$ git commit -am "a nice commit message"` and then `$ git push origin master`

## Contributors
Thanks to [AJ](https://twitter.com/ajlkn) for the website template which I enhanced for [jekyll](http://jekyllrb.com/).


