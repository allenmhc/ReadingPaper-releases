# ReadingPaper — releases

Download links and the [Sparkle](https://sparkle-project.org) update feed for **ReadingPaper**, a
native macOS client for [Instapaper](https://www.instapaper.com). This repository holds only the
disk images and `appcast.xml`; there is no source here.

ReadingPaper is an unaffiliated third-party client built by [@allenmhc](https://github.com/allenmhc)
for personal use. It is not made by, endorsed by, or connected with Instapaper.

## Install

Grab the newest `.dmg` from [Releases](../../releases), open it, and drag **ReadingPaper** into your
Applications folder.

The app is ad-hoc signed rather than notarized, so the *first* launch needs one extra step:
**right-click (or Control-click) ReadingPaper → Open → Open**. After that it launches normally, and
updates install without any prompt.

## Updates

ReadingPaper checks `appcast.xml` daily and installs new versions in the background — there's also
**ReadingPaper ▸ Check for Updates…**. Every disk image is signed with an EdDSA key whose public
half is compiled into the app, so an update only installs if it genuinely came from this feed.

Feed URL: `https://raw.githubusercontent.com/allenmhc/ReadingPaper-releases/main/appcast.xml`
