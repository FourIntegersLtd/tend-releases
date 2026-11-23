# Tend

**Tend keeps your Mac tidy without you having to think about it.** It names and files the things you download, and it finds space you can safely free. It lives in your Dock and menu bar, and a companion iPhone app does the same job for the files on your phone.

**[Download the latest version for Mac](../../releases/latest)** (pick `Tend-x.y.z.dmg`)

---

## What it does

### Tidy: your downloads, sorted
When a file lands in your Downloads folder, Tend reads it and works out what it is. A PDF that is a gas bill becomes **"British Gas bill – March 2026.pdf"** and goes into your Bills folder. A screenshot, a payslip, a contract: each gets a sensible name and a sensible home.

- Tend files the ones it is sure about, and **asks you about the ones it isn't**. You can accept, rename or skip.
- **Teach it once.** Tell Tend "anything containing *british gas* goes to Bills" and it remembers.
- It **flags duplicates** (the same file downloaded twice) instead of filing a second copy.
- Everything it does is written to a **History** list, and you can **undo** a move.

### Space: find room safely
Tend looks for things that are safe to clear, such as old app caches, build folders, finished project copies, old simulators and stale downloads, and tells you how much each would free.

- You choose what to clear. Nothing is cleared without you.
- Most items go into a **Holding area for 30 days** before they are really deleted, so you can **put them back** if you change your mind. "Empty now" is there if you want the space straight away.
- Cleaning up caches and build folders (which the apps rebuild on their own) is done directly, and is logged.

### Your iPhone
The iPhone app (through TestFlight for now) organises the folders you choose on your phone, and has a Share option so you can send a file from any app to Tend. You can also **pair your iPhone with your Mac** (scan a code shown on the Mac) and send files between them over your home Wi-Fi. A file that you "move" from the Mac goes to the Holding area, never straight to the bin.

---

## What to expect the first time

1. Open the downloaded `.dmg` and drag **Tend** into **Applications**, then open it. It is signed and checked by Apple, so you should see no warning.
2. Tend opens its window every time you start it and stays in your Dock, like any Mac app. Its menu-bar icon gives quick access: the **⋯** menu there has Pause, Check for Updates and Quit.
3. It will ask permission to read the folders you choose (Downloads, Desktop, Documents). Say yes only to the ones you want it to look after.
4. **Dry-run is ON the first time.** Tend shows you what it *would* do and **changes nothing** until you turn dry-run off in Settings. Look at its suggestions for a day, then switch it off when you trust it.
5. Tend never touches protected places such as system folders, and every action is recorded before it happens.

## Privacy, in plain terms

- **No account, no sign-up, no tracking, no analytics.** Tend is built for one person on one Mac.
- Reading and naming files happens **on your Mac**, using Apple's built-in AI. Your files, names and text never leave it.
- Your iPhone and Mac talk to each other directly over your Wi-Fi, encrypted with a key made when you paired. Nothing goes through a server.

## Updates
Tend checks for a new version when it opens and every hour after that, and offers to install it. You can also choose **Tend ▸ Check for Updates…** or use the **⋯** menu in the menu-bar pop-over. Updates are downloaded from this page and checked before they are installed.

## Needs
- A Mac with Apple silicon (M1 or later), running **macOS 26 or newer**.

## Good to know
This is an early version, built and tested for personal use. Pairing with an iPhone and sharing from other apps are the newest parts, so please tell us if anything looks wrong.
