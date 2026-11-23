<p align="center">
  <img src="docs/icon.png" width="112" alt="Revelation app icon">
</p>

<h1 align="center">Revelation Presenter</h1>

<p align="center">
  Songs, Bible passages and slides for church services on the Mac,<br>
  with a preview the congregation never sees.
</p>

<p align="center">
  <a href="https://github.com/BnS2/revelation-presenter/releases/latest"><b>Download for Mac</b></a>
  &nbsp;·&nbsp; Apple Silicon &nbsp;·&nbsp; macOS 13 or later
</p>

<p align="center">
  or with Homebrew: <code>brew install --cask bns2/tap/revelation</code> (see <a href="#install">Install</a>)
</p>

![The Present screen: service order on the left, the next slide in Preview, and what the audience sees in Live](docs/screenshots/present.jpg)

## Highlights

- **Preview first, then show it.** Every slide waits in Preview until you press
  Enter. The audience only ever sees what you chose to send.
- **Two Bible versions side by side.** King James and Ang Dating Biblia are
  included. Add another version from a GetBible or Zefania file.
- **Find a verse as it's announced.** Type `gen 1 4` or say "John 3:16" and it's
  ready in Preview, without touching the prepared service.
- **A songbook that remembers.** Save a song once and reuse it every week; each
  song lists the services that used it.
- **Bring what you already have.** Turn a whole Sunday PowerPoint into a service
  of editable songs and readings, or bring in PDFs (including Canva exports),
  photos, or lyrics typed straight in.
- **Find the words online.** Search a free lyrics database, check the words, and
  save the song to your songbook.
- **Free backgrounds and fonts.** A searchable library of CC0 pictures with
  credits, and open-licence fonts, kept on the Mac for offline use.
- **Your logo, whole.** Show your church logo on the blank screen or behind the
  words without cropping, at the size, position and background colour you choose.
- **Plan by dragging.** Drag a service to another day in the calendar.
- **No surprises mid-service.** The Mac stays awake while you present. If the
  TV sleeps or a cable slips, the slides wait in a window instead of covering
  your controls, then go back to the TV.
- **Made for the keyboard and the clicker.** Right Arrow or Space for the next slide,
  B to blank the audience screen, and `/` to find a passage or song.
- **Everything stays on your Mac.** No account, no subscription. One backup file
  moves the whole library to another Mac.
- **Updates itself.** When a new version is out, the app offers it, and installs it
  only when you say so.

## A closer look

### Plan the service

Name the groups yourself (opening songs, Scripture reading, announcements, and so on),
fill them from the library, and drag them into order. Clicking a slide only
previews it.

![The Service screen with groups of songs and readings, and Amazing Grace previewed over a mountain background](docs/screenshots/service.jpg)

### Read in two languages at once

A reading can show one or two versions on the same slide, verse by verse, so the
reader and the congregation can follow along.

![Psalm 23 live in King James and Ang Dating Biblia side by side](docs/screenshots/present-bible.jpg)

### Browse and save readings

Pick a book, a chapter and a range of verses, and save it as a reading for this
service or a later one.

![The Bible screen showing Psalm 23 with a verse range and Save as reading](docs/screenshots/bible.jpg)

### Keep one songbook

See every slide of a song at once, the songwriter's credit line, and the
services where you used it.

![The Songs screen showing Blessed Assurance, its three slides and the services that used it](docs/screenshots/songs.jpg)

### Find the words

Search a free lyrics database by title, artist or a line you remember, read the
words, and check them before they go into your songbook. Songs you already have
are marked.

![Find lyrics online with two public-domain hymns found for "grace", one already in the songbook](docs/screenshots/lyrics.jpg)

### Pick a background

Browse free CC0 backgrounds from Wikimedia Commons, download the ones you like,
and use them for every song or for one song.

![The template library with mountain, ocean, night sky and Bible backgrounds](docs/screenshots/templates.jpg)

<sub>Screenshots use public-domain hymns and Bible text (KJV, Ang Dating Biblia 1905)
and CC0 backgrounds.</sub>

## Install

Revelation runs on Apple Silicon Macs (M1 or later) with macOS 13 or later. It
doesn't run on Intel Macs.

With [Homebrew](https://brew.sh):

```sh
brew tap bns2/tap
brew trust bns2/tap
brew install --cask bns2/tap/revelation
```

Homebrew installs casks from other taps only after `brew trust`. Revelation
updates itself, so `brew upgrade` skips it unless you add `--greedy`.

Or get the latest `.dmg` from
[Releases](https://github.com/BnS2/revelation-presenter/releases/latest).

The app isn't signed with an Apple Developer ID yet, so either way macOS asks for
permission the first time you open it:

1. Open the `.dmg` and drag Revelation into Applications (Homebrew does this for you).
2. Open Revelation. When macOS says it can't verify the developer, click **Done**.
3. Go to **System Settings > Privacy & Security**, scroll down to **Security** and
   click **Open Anyway** next to Revelation. Enter your Mac password.

From then on it opens like any other app.

## Songs

A new install starts with an empty songbook. To use songs another church has
shared, choose **Import a songbook** on the Songs screen or in
**Settings > Library**.

---

This repository only hosts the downloads. The app also checks here for updates.
