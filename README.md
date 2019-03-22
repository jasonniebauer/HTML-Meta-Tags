# HTML Meta Tags
SEO friendly meta tags for HTML.

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
