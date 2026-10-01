<p align="center"><img src="docs/icon.png" width="128" alt="Canvas Cowork icon"></p>

<h1 align="center">Canvas Cowork</h1>

<p align="center">
Your Canvas, Piazza and lecture recordings in one Mac app,<br>
and in Claude and Codex through MCP.
</p>

<p align="center">
<a href="https://github.com/jcasalmo/canvas-cowork/releases/latest/download/Canvas-Cowork.dmg"><img src="docs/download-button.svg" width="300" alt="Download Canvas Cowork for Mac"></a>
</p>

<p align="center"><sub><a href="https://github.com/jcasalmo/canvas-cowork/releases">What's new and older versions</a></sub></p>

---

## What it does

- **Ask Claude or Codex about your classes.** What's due, your grades, syllabi and grading
  policies, Piazza posts, and (at U-M) what was said in lecture, answered from your own
  Canvas.
- **A Mac app for your classes.** Courses, assignments, announcements, files, Piazza and
  lecture recordings in one window.
- **Lecture transcripts, even before captions are out (U-M).** Lectures that don't have
  captions yet can be transcribed on your Mac with Whisper (Apple silicon Macs). Only the
  audio is downloaded, and nothing is uploaded.
- **Drafts you review, never automatic submissions.** The AI can draft a submission or
  reply; it waits in the app's Review tab until you edit it and click Submit yourself.
  Graded quizzes can't be answered.

## Who it's for

Students at schools that use Canvas. Setup asks which school:

- **University of Michigan:** Canvas, Piazza, and CAEN Lecture Capture recordings
  (mostly College of Engineering courses), through U-M Weblogin.
- **Cal Poly San Luis Obispo:** Canvas and Piazza, through the Cal Poly sign-in.
- **Another school:** enter your Canvas address. Canvas and Piazza work wherever you
  sign in to Canvas through your school's own login page.

Lecture recordings and transcripts are U-M only.

You need:

- a Mac on macOS 14 (Sonoma) or later, Apple silicon or Intel,
- the [Claude](https://claude.ai/download) desktop app (Code tab) or the Codex app, on a
  plan that includes them,
- Google Chrome is recommended for the sign-in window. Without it, setup downloads
  Chromium.

## Get started

1. **[Download Canvas Cowork](https://github.com/jcasalmo/canvas-cowork/releases/latest/download/Canvas-Cowork.dmg)**
   and drag it into Applications.
2. **Open Canvas Cowork.** It walks you through a few quick steps: pick your school,
   install the helpers, sign in, and pick Claude or Codex.
3. **Chat.** A new chat opens in your School folder with a first question typed in. Press
   Return.

**Next time:** click **Ask Claude** (or **Ask Codex**) in Canvas Cowork's sidebar. Chats
started that way know about your classes; your other chats aren't affected. For ideas,
open **What Can I Ask?** in the sidebar.

## Updates

The app updates itself. It checks once a day, downloads new versions in the
background, and installs them when you quit. **Canvas Cowork → Check for Updates…**
checks right away. Updates are signed; the app only installs ones that carry the
matching signature, and macOS checks Apple's notarization as well.

## Privacy

- Everything runs on your Mac. Your school sessions are stored in
  `~/.local/share/canvas-mcp/.env` and `~/.local/share/piazza-mcp/.env`, readable only by
  your account. Don't share those files.
- Sessions expire now and then. When the dot at the bottom left of the app's sidebar turns
  orange, click it to sign in again.
- When you use it from Claude or Codex, what the AI reads from Canvas goes to that AI
  service like anything else in the chat.

## Not affiliated

An independent student project. Not made by or affiliated with the University of
Michigan, Cal Poly, any other school, Instructure (Canvas), Piazza, Anthropic or OpenAI. Follow each course's policy
on using AI.
