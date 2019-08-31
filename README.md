
# typeface-iranyekan

The CSS and web font files to easily self-host “IRANSans”.

## Install

`npm install --save typeface-iransans`

`yarn add typeface-iransans`

## Use

Since the font is licensed you have to download the fonts from the [producer website](https://fontiran.com/%d8%ae%d8%a7%d9%86%d9%88%d8%a7%d8%af%d9%87-%d9%81%d9%88%d9%86%d8%aa-%d8%a7%db%8c%d8%b1%d8%a7%d9%86-%d8%b3%d9%86-%d8%b3%d8%b1%db%8c%d9%81-iran-sans-%d9%be%d9%86%d8%ac-%d9%88%d8%b2%d9%86-%d9%87%d9%85/) and then put all the web fonts in `files`.

Typefaces assume you’re using webpack to process CSS and files. Each typeface
package includes all necessary font files (woff2, woff, eot, ttf, svg) and
a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built
with Webpack will work out of the box with Typefaces such as [Gatsby](https://github.com/gatsbyjs/gatsby)
and [Create React App](https://github.com/facebookincubator/create-react-app).

To use, simply require the package in your project’s entry file e.g.
