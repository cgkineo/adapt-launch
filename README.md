# adapt-launchNewWindow

```javascript
//config.json
    "_launchNewWindow": {
        "_isEnabled": true,
        "_stopSessionInitialize": true,
        "_activeOnPages": [
            "index_lms.html"
        ],
        "_activeOnSelector": ".os-ios",
        "_target": "courseWin",
        "_strWindowFeatures": "width={{width}},height={{height}},menubar=no,location=no,directories=no,resizable=yes,scrollbars=yes",
        "_delay": 500,
        "preLaunchTitle": "The course should now open in a new browser window.",
        "preLaunchBody": "If this does not occur, please deactivate any popup blocking software - then <a href=\"{{href}}\" target=\"_blank\">click here</a> or refresh this page to try again.",
        "launchTitle": "The course should now be open in a new browser window.",
        "launchBody": "Please ensure you don't close or do anything in this window whilst the course is in progress.",
        "closedTitle": "You have closed the course.",
        "closedBody": "Please close this window to continue."
    }
```
The `_activeOnSelector` can be a comma-separated list if you want to target multiple platforms/browsers e.g. `"_activeOnSelector": ".os-ios, .os-android"`
