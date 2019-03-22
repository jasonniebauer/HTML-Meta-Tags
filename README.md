# HTML Meta Tags
SEO friendly meta tags for HTML.

**Table of Contents**  
* [Basic HTML Meta Tags](#basics-html-meta-tags)
* [OpenGraph Meta Tags](#opengraph-meta-tags)
* [Custom Meta Tags](#custom-meta-tags)

| Attribute             | Value | Description                           |
|:----------------------|:------|:---------------------------------|
| charset    | *character_set* | Specifies the character encoding for the HTML document |
| content    | *text*      | Gives the value associated with the http-equiv or name attribute |
| http-equiv | content-type, default-style | Provides an HTTP header for the information/value of the content attribute |
| http-equiv |             | Refresh document every 30 seconds |
| name       | keyword     |  Define keywords for search engines    |
| name       | description | Define a description of your web page |
| name       | author      | Define the author of a page           |
| name       | viewport    | Setting the viewport to make your website look good on all device |

### Charset
Specify your document's character encoding with the `charset` meta tag.

**An example code snippet for charset tag use:**  
```
<meta charset="utf-8">
```

### Content Type

**An example code snippet for content type tag use:**  
```
<meta http-equiv=”Content-Type” content=”text/html; charset=utf-8″/>
```

### Keyword

**An example code snippet for the keyword meta tag:**  
```

```

### Description

**An example code snippet for the description meta tag:**  
```

```

### Author

**An example code snippet for the author meta tag:**
```

```

### Viewport
**An example code snippet for the viewport meta tag:**  
```
<meta name=”viewport” content=”width=device-width, initial-scale=1″>
```

## Robots Meta Tags

| Value | Description |
|:------|:------------|
| Nofollow | Tells crawlers not to follow any of the links listed on that page, and also not to pass any equity to linked page |
| Noindex | Tells crawlers not to index that page |
| Noimageindex | Tells crawlers not to index images from that page |
| Noarchive | Tells crawlers not to include a cached version |

**An example code snippet for the robot meta tag:**  
```
<meta name=”robot” content=”noindex, nofollow”>
```

## Open Graph Meta Tags for Social

| Attribute | Value          | Description |
|:----------|:---------------|:------------|
| property  | og:image       | |
| property  | og:image       | |
| property  | og:site_name   | |
| property  | og:description | |

**Title example**  
```
<meta property=”og:title” content=”Article about tags”/>
```

**Image example**  
```
<meta property=”og:image” content=”https://example.com/img/facebooklogo.png”/>
```

**Site name example**  
```
<meta property=”og:site_name” content=”SEO blog”/>
```

**Description example**
```
<meta property=”og:description” content=”This article will talk about tags”/>
```

## Twitter Meta Tags

```
<meta name="twitter:title" content="Mozilla Developer Network">
```

## Icons

```
<!-- third-generation iPad with high-resolution Retina display: -->
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="https://developer.cdn.mozilla.net/static/img/favicon144.a6e4162070f4.png">
<!-- iPhone with high-resolution Retina display: -->
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="https://developer.cdn.mozilla.net/static/img/favicon114.0e9fabd44f85.png">
<!-- first- and second-generation iPad: -->
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="https://developer.cdn.mozilla.net/static/img/favicon72.8ff9d87c82a0.png">
<!-- non-Retina iPhone, iPod Touch, and Android 2.1+ devices: -->
<link rel="apple-touch-icon-precomposed" href="https://developer.cdn.mozilla.net/static/img/favicon57.a2490b9a2d76.png">
<!-- basic favicon -->
<link rel="shortcut icon" href="https://developer.cdn.mozilla.net/static/img/favicon32.png">
```

### Shortcut Icon
```
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

## Language
Set the primary language of the document.

```
<html lang="en-US">
```

## Basic HTML Meta Tags
```
<meta name="keywords" content="your, tags"/>
<meta name="description" content="150 words"/>
<meta name="subject" content="your website's subject">
<meta name="copyright"content="company name">
<meta name="language" content="ES">
<meta name="robots" content="index,follow" />
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm" />
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">
<meta name="Classification" content="Business">
<meta name="author" content="name, email@hotmail.com">
<meta name="designer" content="">
<meta name="copyright" content="">
<meta name="reply-to" content="email@hotmail.com">
<meta name="owner" content="">
<meta name="url" content="http://www.websiteaddrress.com">
<meta name="identifier-URL" content="http://www.websiteaddress.com">
<meta name="directory" content="submission">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="rating" content="General">
<meta name="revisit-after" content="7 days">
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
```

## OpenGraph Meta Tags
```
<meta name="og:title" content="The Rock"/>
<meta name="og:type" content="movie"/>
<meta name="og:url" content="http://www.imdb.com/title/tt0117500/"/>
<meta name="og:image" content="http://ia.media-imdb.com/rock.jpg"/>
<meta name="og:site_name" content="IMDb"/>
<meta name="og:description" content="A group of U.S. Marines, under command of..."/>

<meta name="fb:page_id" content="43929265776" />

<meta name="og:email" content="me@example.com"/>
<meta name="og:phone_number" content="650-123-4567"/>
<meta name="og:fax_number" content="+1-415-123-4567"/>

<meta name="og:latitude" content="37.416343"/>
<meta name="og:longitude" content="-122.153013"/>
<meta name="og:street-address" content="1601 S California Ave"/>
<meta name="og:locality" content="Palo Alto"/>
<meta name="og:region" content="CA"/>
<meta name="og:postal-code" content="94304"/>
<meta name="og:country-name" content="USA"/>

<meta property="og:type" content="game.achievement"/>
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT"/>

<meta property="og:video" content="http://example.com/awesome.swf" />
<meta property="og:video:height" content="640" />
<meta property="og:video:width" content="385" />
<meta property="og:video:type" content="application/x-shockwave-flash" />
<meta property="og:video" content="http://example.com/html5.mp4" />
<meta property="og:video:type" content="video/mp4" />
<meta property="og:video" content="http://example.com/fallback.vid" />
<meta property="og:video:type" content="text/html" />

<meta property="og:audio" content="http://example.com/amazing.mp3" />
<meta property="og:audio:title" content="Amazing Song" />
<meta property="og:audio:artist" content="Amazing Band" />
<meta property="og:audio:album" content="Amazing Album" />
<meta property="og:audio:type" content="application/mp3" />
```

## Custom Meta Tags
Use custom meta tags to store data that you need in javascript, instead of hard-coding that data into your javascript. I store my Google Analytics code in meta tags. Here's some examples:

```
<meta name="google-analytics" content="1-AHFKALJ"/>
<meta name="disqus" content="abcdefg"/>
<meta name="uservoice" content="asdfasdf"/>
<meta name="mixpanel" content="asdfasdf"/>
```

