This is a fork of http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/ (v1.3)

FWIW, there is a new Tooltip widget under active development in jQuery UI and was added as part of the UI 1.9 Milestone 1 release. Read this [blog post] (http://blog.jqueryui.com/2010/05/jquery-ui-19m1-tooltip/)

# v1.4
### Added an option:
```javascript
{
  hideDelay: 30
}
```
The number of milliseconds before the tooltip disappears on mouseout. Defaults to 30ms. A value of 0 will make it disappear immediately. This is useful, if you have links in your tooltip content and would like the user to be able to click on them.

### $.tooltip.restore(elem/selector)
Calling $.tooltip.restore will remove the tooltip functionality from the element.

```javascript
$.tooltip.restore('a');
```

# Documentation (v1.3)
For documentation, please refer to http://docs.jquery.com/Plugins/Tooltip

# Demos (v1.3)
For demos, please refer to http://jquery.bassistance.de/tooltip/demo/

# Optional dependency
[bgiframe plugin] (https://github.com/brandonaaron/bgiframe) to fix select problems in IE

# License
Dual licensed under the MIT and GPL licenses:
  http://www.opensource.org/licenses/mit-license.php
  http://www.gnu.org/licenses/gpl.html
  
*Copyright (c) 2006 - 2008 Jörn Zaefferer*
