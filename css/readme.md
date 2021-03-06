# Mable CDN: CSS

This file is absolutely necessary to use Mable. Add it anywhere in the `<head>` section of all HTML documents.

Example:

```html
<head>
	<!-- Page Info -->
	<title>This is a sample Mable HTML Header</title>
	<meta name="description" content="Page Description">
	<meta name="keywords" content="Page, Tags">
	<meta property="og:image" content="https://full-url">
	<link href="../images/brand/favicon.png" rel="shortcut icon">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<!-- CSS Sheets -->
	<link type="text/css" rel="stylesheet" href="css/style.css">
		
	<!-- Themes -->
	<link type="text/css" rel="stylesheet" href="themes/sample-theme" id="custom-theme-sheet">

	<!-- Packages -->
	<link type="text/css" rel="stylesheet" href="packages/sample-package.css">
</head>
```

## Latest CSS File

This file may contain bugs, it is recommended to use the "Release" CSS file, or a specific release (not available during beta)

```
<link rel="stylesheet" type="text/css" href="https://cdn.mablesite.com/css/style.css">
```
