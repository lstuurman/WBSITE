### SOME NOTES ABOUT SEO 

## BASICS
HTML Meta data:
- make shure title,discription and keywords are complete and good
- include favicon 
- Compress your website : Minify? your css,html and javascript (http://minifycode.com)
- Put important keywords EVERYWHERE

## IMAGES
Faster webpages -->> better searchable
Hence -> compress imagas or video content  (compressjpeg.com)
(Free images on unsplash)

ALT TAGS:
<img alt='my discription of the image'>
also:
You can give most html tags a title :
<a href="https//google.com"title="google search engine">Google</a>

## MOBILE FRIENDLY 
**MEDIA QUERRIES** -->> enable dynamic styling for phone vs desktop


### NEW NOTES 

-Content (what are our costumers looking for?)
-Strategy (How can we quide them through/to our product?)
-Technology(HORAY!)

## HOW DOES GOOGLE WORK :
- Start with list of urls
- google 'crawls' through urls -->> makes GET requests
- Processes the info received
- Put that info into a INDEX (queriable identification)
    - google runs javascript
    - other crawlers might not run javascript

- what is a good page for specific query

### As developers we can only influence
#### CRAWLING
Link between pages of website **USE ACTUAL LINKS**
Don't use # in urls

Create sitemap to make important parts of website easily accesible for google crawler

React Helmet (similar to django context attributes)
In helmet difine canonical links (preferred url when multiple urls point to same page)

Use <meta name="robots" content="noindex"/> to make crawler ignore url
robots.txt (file that points to stuff that should be ignored)

Add strucutured data

Invest in serverside rendering
(Gatsby and Next.js)
Lazy Loading
Dynamic Rendering

Make shure pages that don't exist return a 404
fallbackhandling
g.co/searchconsole
#### RENDERING
#### INDEXING


## COOKIES
Useful JS librarie for cookies : js-cookie

### USEFULL TOTURALS
javascript DOM and other stuff : https://www.youtube.com/watch?v=eaLKqoB9Fu0&list=PLWKjhJtqVAbllLK6r2dnGjUVWB_cFNcuO&ab_channel=freeCodeCamp.org