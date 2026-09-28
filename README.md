<p align="center"><img src="docs/icon.png" width="128" alt="Canvas Cowork icon"></p>

<h1 align="center">Canvas Cowork</h1>

<p align="center">
Your University of Michigan Canvas, Piazza and lecture recordings in one Mac app,<br>
and in Claude and Codex through MCP.
</p>

<p align="center">
<a href="https://github.com/jcasalmo/canvas-cowork/releases/latest/download/Canvas-Cowork.dmg"><b>Download for Mac</b></a>
&nbsp;·&nbsp;
<a href="https://github.com/jcasalmo/canvas-cowork/releases">All releases</a>
</p>

---

## What it does

- **A Mac app for your classes.** Courses, what's due, grades, announcements, files, Piazza
  and lecture recordings with searchable transcripts, in one window.
- **Your classes in Claude and Codex.** Setup makes a School folder. Chats you start there
  can look up assignments, due dates, syllabi and grading policies, Piazza posts and
  what was said in lecture. Chats anywhere else are left alone.
- **Drafts you review, never automatic submissions.** The AI can stage a draft of a
  submission, discussion reply or comment. It waits in the app's Review tab until you
  edit it and click Submit yourself. Graded quizzes can't be answered in any mode.

## Who it's for

U-M students. It signs in through U-M Weblogin and reads U-M Canvas
(`umich.instructure.com`), Piazza courses linked from Canvas, and CAEN Lecture Capture
(mostly College of Engineering courses). It won't work with other schools.

You need:

- a Mac on macOS 14 (Sonoma) or later, Apple silicon or Intel,
- the [Claude](https://claude.ai/download) desktop app (Code tab) or the Codex app, on a
  plan that includes them,
- Google Chrome is recommended for the sign-in window. Without it, setup downloads
  Chromium.

## Install

1. [Download Canvas-Cowork.dmg](https://github.com/jcasalmo/canvas-cowork/releases/latest/download/Canvas-Cowork.dmg)
   and drag **Canvas Cowork** into Applications.
2. Open it. It's signed and notarized by Apple, so macOS only asks the usual
   "downloaded from the internet" question.
3. A setup window walks you through three steps:
   1. **Install the MCP servers:** one click. Downloads Python and its packages
      (about 250 MB) into `~/.local/share`.
   2. **Make your School folder:** one click each for Claude and Codex, then **Open**.
      The first time, Claude asks whether to trust the folder; click Trust.
   3. **Sign in to U-M:** a browser window opens. Sign in with Weblogin and Duo once.
      This covers Canvas, Piazza and lecture capture.
4. In a chat in the School folder, ask something like *"what's due this week?"*

Reopen setup any time from the **Canvas Cowork** menu → **Set Up MCP…**

## Updates

The app updates itself. It checks once a day, downloads new versions in the
background, and installs them when you quit. **Canvas Cowork → Check for Updates…**
checks right away. Updates are signed; the app only installs ones that carry the
matching signature, and macOS checks Apple's notarization as well.

## Privacy

- Everything runs on your Mac. Your U-M sessions are stored in
  `~/.local/share/canvas-mcp/.env` and `~/.local/share/piazza-mcp/.env`, readable only by
  your account. Don't share those files.
- Sessions expire now and then. When the dot at the bottom left of the app's sidebar turns
  orange, click it to sign in again.
- When you use it from Claude or Codex, what the AI reads from Canvas goes to that AI
  service like anything else in the chat.
- **Anonymous usage counts.** So I can see how many people use it each week, the app
  sends at most one ping a day for each of these: you opened the app, you used Canvas or
  Piazza from Claude or Codex, you finished setup. A ping holds a random install ID made on
  your Mac, the event name, and the app version, macOS version and CPU type. Never your
  name, email, courses, sessions or chats, and no IP addresses are stored. Turn it off
  in the setup window (**Share anonymous usage counts**).

## Not affiliated

An independent student project. Not made by or affiliated with the University of
Michigan, Instructure (Canvas), Piazza, Anthropic or OpenAI. Follow each course's policy
on using AI.
