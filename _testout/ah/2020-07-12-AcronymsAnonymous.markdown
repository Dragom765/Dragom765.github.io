---
layout: post
title:  "Acronym Aid Bot"
brief:  "An acronym assistance Slack bot"
categories:
  - MySQL
  - Expressjs
  - Node.js
  - jQuery
  - Bootstrap
  - Ajax
source: https://github.com/isibley765/planner-project
previews:
    - image: DisplayInfo.png
titleImage: AcronymsAnonymousIcon.png
---

A project I picked up after one of the ROV MATE competitions, this was started
in hopes that it would help keep track of the sheer amount of acronyms we would
always wind up with, and were inevitably different per team.

This Acronym Bot app works with Slack's API to allow for Purdue ROV users to look
up acronyms through a simple text-based interface native to Slack's behavior. This
is done in a Nodejs server, taking advantage of the threading of Node's JavaScript
base, and responding privately to users in direct messages or even in user-specific
messages in a public channel for discresion, so users could look up acronyms at any
time without interrupting conversation, or be subject to any social pressures if
present.

The stretch goal was to make this a bit remeniscent of a Big Brother bot, and have
it skim over all chats sent on the Purdue ROV slack, check for words, and prompt
slack users for potential acronyms to keep the update process from being hugely
manual. But there was a limit on feasibility; while I could pass things through a
dictionary API, it became an enormous challenge to account for typo's, different
languages, slang, etc. So, this feature was left off in the final form.

---
