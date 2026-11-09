WTVFC Digital Signage v4.44 - automatic full-site reload

Install index.html to dev repo, then promote to live. The sign checks published index.html every 60 seconds and reloads at the end of a screen rotation if it detects a newer version. Do not remove/rename the <title> version, or the meta wtvfc-build-version value. Keep the version numbers updated in future releases.

Persistent Google Sheets endpoint and local preferences remain in localStorage. This feature only detects new HTML builds; Google Sheet changes continue to update separately every 30 seconds.

This ZIP includes all existing six screen assets.
