# RC-Tooltips

RC-Tooltips is a small javasript-library that adds tooltips functionality for web pages. 

### There are standart tooltips in browsers, aren't they?

They were. Latest versions of Google Chrome sometimes doesn't show standart tooltips which was maded with attribute "title" on elements.

### How it works?

Two steps:

1. Add next lines to *head* section of your web-pages:
```
<link  type="text/css" rel="stylesheet" href="pathToLibrary/tooltip/tooltip.css" />
<script type="text/javascript" src="pathToLibrary/tooltip/tooltip.js"></script>
```

2. Add "rc-title" attribute for elements which is needed to show hints on mouseover. For example:
```
<span rc-title="This is hint">some text</span>
```

### License

This project is published under MIT License.
