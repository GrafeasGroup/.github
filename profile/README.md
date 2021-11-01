## Welcome to the code!

The best way to describe our organization is to start with our mission statement:

> We provide a framework for crowd-sourcing accessible, text-based content for all Internet users, regardless of disability, access devices, or data restrictions.

There is a lot of content on the internet that is inaccessible to those with visual restrictions, no data plan, or otherwise an inability to load content. A lot of that content is hidden inside images — images that a phone with low data cannot load, or assistive screen reading technology cannot interpret. We are pioneering a system for locating this content and passing it to volunteers to create pure text representations so that everyone can access it.

This system, so far, has been deployed on Reddit.com under the subreddit [r/TranscribersOfReddit](https://reddit.com/r/transcribersofreddit/wiki/index) and features an innovative use of gamification concepts and volunteering to engage users and improve communities. Starting with just two people in April of 2017, over **4500** volunteers have transcribed more than **185,000** pieces of content in the following four years. We currently serve a combined digital population of approximately one million Reddit subscribers.

---

All of our code (that reasonably can be) is open sourced and it can be found right here! Our primary codebases are separated into two groups: the bots that help us run the subreddit and the bots that help us run the organization.

### The ToR Family

The bots that power Transcribers of Reddit (ToR) all directly interact with Reddit primarily and with our org bots. Those repositories are:

- [ToR](https://github.com/GrafeasGroup/tor) — the primary bot that all our volunteers interact with. Lives on Reddit as [u/transcriberofreddit](https://reddit.com/u/transcribersofreddit)
- [ToR Archivist](https://github.com/GrafeasGroup/tor_archivist) — the bot that keeps the queue clean and archives the completed posts for those who need them! Known online as [u/ToR_archivist](https://reddit.com/u/tor_archivist) and runs [The Archive](https://reddit.com/r/ToR_Archive)
- [ToR OCR](https://github.com/GrafeasGroup/tor_ocr) — to give our volunteers a little boost, the bot attempts to pull the text from the image using [OCR (Optical Character Recognition)](https://en.wikipedia.org/wiki/Optical_character_recognition) to get people started

### The Organzation Family

Like any modern organization, there's a bunch of automation going on behind the scenes that helps us do our jobs! Our three primary bots here are:

- [blossom](https://github.com/GrafeasGroup/blossom) — our data monolith that powers everything and keeps track of All Man Was Not Meant To Know
- [buttercup](https://github.com/GrafeasGroup/buttercup) — an in-progress system for interacting with volunteers in Discord and assisting with moderation
- [bubbles](https://github.com/GrafeasGroup/Bubbles-V2) — a Slack chatbot that helps us get literally anything done

---

## Interested in helping out?

Just take a look at some of our primary repos and dive in! Don't feel bad about asking for help or for clarification about a particular issue that's open — we're always down to help get you started and provide any missing context. We appreciate you, and thanks for helping make the net a better place!
