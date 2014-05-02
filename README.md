<piwik-tracker>
===============

The Piwik (http://www.piwik.org) tracker made with [Google Polymer](http://www.polymer-project.org)


Usage
=====

On your page, include the Polymer scripts (`platform` is required by `Polymer` to work):

```
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/platform.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.3/polymer.js"></script>
```

Then import the Piwik tracker library:

```
<link rel="import" href="src/piwik-element.html">
```

Finally, on your page, add the component `<piwik-tracker>` like that:


```<piwik-tracker piwikUrl="www.example.com" siteId="42"></piwik-tracker>```

* `piwikUrl` points to the URL of the Piwik server (without `http` or `https`, as it will be automatically added).
* `siteId` is the ID of the site that is currently monitored.
 
