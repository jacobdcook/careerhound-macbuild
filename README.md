# careerhound-macbuild

Build runner for the CareerHound macOS app. No source lives here: the workflow
checks out the private repo with a read-only deploy key, builds, launches the
app to check every page opens, and attaches the zip to a release.

Downloads: https://usecareerhound.com/download
