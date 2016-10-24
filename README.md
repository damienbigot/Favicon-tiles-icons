# Favicon
### Code
```
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

###Image size
- 16x16
- 24x24
- 32x32
- 64x64

### Reference
> [What’s in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#Adding_custom_icons_to_your_site) _on MDN_
> [Customizing the Site Icon](https://msdn.microsoft.com/en-us/library/gg491740(v=vs.85).aspx) _on MSDN_

<br />

# Pinned Site _(Windows 8 & 10)_
### Code
```
<meta name="msapplication-square70x70logo" content="images/tinylogo.png">
<meta name="msapplication-square150x150logo" content="images/logo.png">
<meta name="msapplication-wide310x150logo" content="images/widelogo.png">
<meta name="msapplication-square310x310logo" content="images/largelogo.png">
```
```
<meta name="msapplication-TileColor" content="#FF3300">
<meta name="msapplication-TileImage" content="images\tileimage.jpg">
```

###Image size
- 70x70
- 150x150
- 310x150
- 310x310

### Reference
> [Pinned site metadata reference](https://msdn.microsoft.com/en-us/library/dn255024(v=vs.85).aspx) _on MSDN_


<br />

# Pinned Tab Icons _(Safari on OS X El Capitan)_
### Code

```
<link rel="mask-icon" href="website_icon.svg" color="red">
```

###Image size
- 16x16

### Reference
> [Creating Pinned Tab Icons](https://developer.apple.com/library/content/documentation/AppleApplications/Reference/SafariWebContent/pinnedTabs/pinnedTabs.html) _on Apple Developer_


<br />

# Webpage Icon _(Safari on iOS 6, 7 & 8+)_
### Code

```
<link rel="apple-touch-icon" href="/custom_icon.png">
```

```
<link rel="apple-touch-icon" href="touch-icon-iphone.png">
<link rel="apple-touch-icon" sizes="76x76" href="touch-icon-ipad.png">
<link rel="apple-touch-icon" sizes="120x120" href="touch-icon-iphone-retina.png">
<link rel="apple-touch-icon" sizes="152x152" href="touch-icon-ipad-retina.png">
```

###Image size
- 57x57
- 60x60
- 72x72
- 76x76
- 114x144
- 120x120
- 144x144
- 152x152
- 180x180

### Reference
> [Configuring Web Applications](https://developer.apple.com/library/content/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html) _on Apple Developer_
