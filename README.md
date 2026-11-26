<p align="center"><img src="icon.png" width="96" alt="FocusAgent KTI"></p>

# FocusAgent KTI

A study app for KTI students: read lecture files (PDF, PowerPoint, Word), ask an AI tutor about them,
translate into Kurdish (Sorani / Kurmanji), make quizzes, flashcards and Kurdish summaries, take notes,
and stay focused with a distraction detector and Pomodoro timer.
**Everything runs on your own computer** — your lectures, notes and questions never leave it.

### [⬇ Download the latest version for Windows](https://github.com/TensaiSah/FocusAgent-KTI/releases/latest)

On the release page, under **Assets**, click **FocusAgent-KTI-Setup-….exe**.

---

## Installing

FocusAgent runs entirely on your own computer: the AI, the translation and
your notes never leave it. Installing takes two parts — the app itself,
then a one-time download of the AI (FocusAgent guides you through it).

## What you need

- Windows 10 or 11 (64-bit)
- About **6 GB of free disk space** (app ~0.5 GB, AI ~3 GB, translation ~1.4 GB)
- 8 GB of RAM or more recommended
- Internet for the first setup only — after that everything works offline
- A graphics card (NVIDIA RTX or similar) makes the AI much faster, but it
  also works without one: FocusAgent then switches to its Light mode

## 1. Install the app

1. Download **FocusAgent-KTI-Setup-<version>.exe**.
2. Double-click it.
3. Windows may show **"Windows protected your PC"**. That is because the
   installer isn't signed with a paid certificate yet — it doesn't mean
   anything is wrong. Click **More info**, then **Run anyway**.
4. Choose where to install it (the default is fine) and click **Install**.
   No administrator password is needed.
5. Start **FocusAgent KTI** from the desktop or the Start menu.

## 2. First-time setup (inside the app)

On the first start a **"let's get the AI ready"** window opens with three steps:

1. **Ollama** — the program that runs the AI. Click **Install Ollama**: its
   official installer is downloaded and opens; click through it. FocusAgent
   notices by itself when it's ready.
2. **AI model** — click **Download** (about 2 GB). On an older computer
   without a graphics card, also download the **small model** (1.3 GB).
3. **Offline translation** — click **Download** (about 1.4 GB). Needed for
   Translate and the Kurdish Summary.

You can close this window at any time and finish later from
**Settings → First-time setup**. Downloads that get interrupted continue
where they stopped.

## Using it

- **Open file** — PDF, PowerPoint (.pptx), Word (.docx), text or Markdown.
- Ask the AI about the lecture, translate selected text into Kurdish, make
  flashcards, take notes, generate quizzes, and use the Eye Tracker with a
  Pomodoro timer.
- Keyboard shortcuts are listed in **Settings → Keyboard shortcuts**.

## Uninstalling

Windows **Settings → Apps → Installed apps → FocusAgent KTI → Uninstall**.
The uninstaller asks two questions:

1. **"Also delete your FocusAgent data?"** — Yes removes your notes,
   highlights, bookmarks, quiz history, settings and the offline
   translation model (1.4 GB). No keeps them for a later reinstall.
2. **"Also remove the AI?"** (only if Ollama is installed) — Yes uninstalls
   Ollama and deletes all of its AI models (several GB). Choose No if you
   use Ollama for anything else.

Answer Yes to both to remove everything FocusAgent put on the computer.
Installing a newer version of FocusAgent never deletes anything.

For IT staff: `"Uninstall FocusAgent KTI.exe" /S /PURGE` (in the install
folder) removes the app, its data, Ollama and its models without asking.

## Something doesn't work?

- **The AI says "Ollama is not running"** — start Ollama from the Start
  menu (or reopen FocusAgent), then try again.
- **"The AI model … is not installed"** — open **Settings → First-time
  setup** and download it.
- **Translation says it isn't installed** — **Settings → Offline
  translation → Download**.
- **The AI is very slow** — set **Settings → AI performance** to **Light**
  and download the small model in the first-time setup.
