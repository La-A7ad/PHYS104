# PHYS104 Obsidian vault: a casual guide

Hey! This is the vault for PHYS 104. The main part is a set of ray optics notes (Chapter 35 of the textbook) written as questions. You're meant to answer before you peek, which is the whole point. This page shows you how to open it and get around, on Windows or Linux.

**Coverage:** the notes currently go up to Lecture 4 (L3b, dispersion and prisms). More lectures will be added as the course goes on.

## What's in here

- `Notes/PHYS104 Recall/`: the main stuff. Start with `Index.md` in there.
- `Notes/`: a few extra study pages (Cheat Sheet, Drills, Mock Quiz) next to the Recall folder.
- `Lectures/`, `Tutorials/`, `Assignments/`: the course PDFs as they were handed out.
- The textbook isn't included, because of copyright and file size. The notes cite its sections and page numbers, so get your own copy of the 10th edition.
- `.obsidian/`: Obsidian's settings for this vault. Don't delete it.
- `.markdown-collab/` and `.mcp.json`: tool settings you don't need for studying.

## Step 1: install Obsidian

It's free. Get it from [obsidian.md](https://obsidian.md).

- **Windows**: download the installer and run it.
- **Linux**: any of these works:
  - AppImage from obsidian.md: make it executable with `chmod +x Obsidian-*.AppImage`, then run it.
  - Flatpak: `flatpak install flathub md.obsidian.Obsidian`
  - Arch (or CachyOS): the `obsidian` package from the AUR, e.g. `yay -S obsidian`

## Step 2: open this folder as a vault

1. Open Obsidian and choose **Open folder as vault**. Don't pick "Create new vault", or you'll end up with an empty one.
2. Select the `PHYS104` folder itself, the one that holds `README.md` and `.obsidian`.

If the vault opens empty, you probably picked the folder one level too high. Go back and select `PHYS104`.

## Step 3: get around

- **Ctrl+O**: quick switcher. Type a note's name and hit Enter. This is the fastest way to get anywhere.
- **Ctrl+Shift+F**: search every note at once.
- **Ctrl+P**: command palette, for everything else.
- **Ctrl+E**: switch between editing and reading view.
- **Ctrl+click** a `[[link]]` in editing view to jump to it. In reading view, a plain click works.
- The right sidebar has the outline and backlinks. Backlinks show which other notes link to the one you're reading.
- Graph view (the network icon) looks cool, but you won't need it.

Ctrl is the modifier on both Windows and Linux. (It's Cmd on a Mac, but you're not on a Mac, so don't worry about that.)

## How to study with these notes

Open `Notes/PHYS104 Recall/Index.md` and read "How to use it". The short version:

1. Read the question and answer it on paper or in your head. A rough answer counts.
2. Stuck? Open the **Hint** box.
3. Then open the **Answer** box.
4. Tick the concept in the **Recall Log** only when you got it right without a hint.

The boxes look like this in the raw Markdown:

```markdown
> [!question] Question text

> [!success]- Answer
> The answer goes here.
```

The `-` after `success` means the box starts collapsed. Click its title to open it. Try the question before you do.

The **Glossary** is one line per term, and **Tutorials and Assignment** has all the tutorial and assignment questions with worked answers. Use both after you've attempted the questions, not before.

## A few tips

- Obsidian saves as you type. There's no save button.
- Renaming a note through Obsidian updates the links to it automatically. Renaming it in your file manager doesn't.
- Keep images in `Notes/PHYS104 Recall/Attachments/`.
- Your notes are plain Markdown files. If Obsidian ever misbehaves, you can still open them in any text editor.
- If something in the notes looks wrong, tell whoever shared the vault with you.

## About this README

This README was written with help from Claude, an AI assistant made by Anthropic.
