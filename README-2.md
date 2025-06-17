# 📖 Bookmark — A Standard for Structuring Memory

> MIT Licensed, human-first memory structure for agents, tools, and people.

---

## ⚠️ Still in Development

These projects are **actively being built**, refined, and soon to be stress-tested in the real world.

* Features may change as I break, test, and rebuild everything from the ground up
* Some logic is experimental or placeholder until it's solid enough for real deployment
* Nothing gets released until it’s strong enough to be trusted by the people it’s built for

If you’re reading this, you’re early.
If you’re using this, you’re part of the build.

> *“I won’t ship anything I wouldn’t use for myself.”* — Jesse

![status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)

---

## ✨ What is Bookmark?

> \*"The system helps you connect your **books**, **pages**, **marks**, **ribbons**, and **trails** to create custom **Marker Agents**."

**Bookmark** is a memory-first, Markdown-native standard for organizing thought, action, and intent. It reimagines the traditional file system as a living, breathing **storybook-style environment** — made of **books**, **pages**, **marks**, **markers**, **ribbons**, and **trails** — where every interaction helps the system construct a memory-aware interface.

It is:

* MIT Licensed, like Storybook, Tailwind, and the best open tools
* Designed to work with `.book`, `.mark`, `.marker`, `.ribbon`, `.trail`, and `.mstp` formats
* UI-agnostic — works in terminal, GUI, markdown viewers, or AR
* Not a book simulator, but a developer storytelling structure — like Storybook, but for logic and memory

---

## 📘 Core Concepts

| Concept      | Folder       | Description                                                    |
| ------------ | ------------ | -------------------------------------------------------------- |
| **Bookmark** | `.bookmark/` | Memory environment and root for all knowledge components       |
| **Bookcase** | `bookcase/`  | A collection of books ready to be used, routed, or interpreted |

| Concept  | File    | Description                                                 |
| -------- | ------- | ----------------------------------------------------------- |
| **MSTP** | `.mstp` | Markdown Storytelling Protocol — system-generated logic     |
| **Book** | `.book` | A collection of pages, marks, markers, ribbons, and trails. |

| Concept    | File/Folder           | Description                                         |
| ---------- | --------------------- | --------------------------------------------------- |
| **Page**   | `.page`, `pages/`     | A single context snapshot                           |
| **Mark**   | `.mark`, `marks/`     | A reusable memory anchor or logic tag               |
| **Marker** | `.marker`, `markers/` | The tool or method that connects and triggers marks |
| **Ribbon** | `.ribbon`, `ribbons/` | Starting point of a memory flow                     |
| **Trail**  | `.trail`, `trails/`   | System-tracked logs for each marker                 |

---

## 📂 File Hierarchy Example

```
.bookmark/
├── bookcase/
│   ├── me.book
│   ├── fed.book
│   ├── elda.book
│   ├── hwy.book
│   ├── eco.book
│   └── openhwy.book
├── marks/
│   ├── scan.mark
│   ├── sign.mark
│   ├── check.mark
│   ├── whisper.mark
│   └── process.mark
├── pages/
│   ├── process-checker.page
│   ├── bugfix-notes.page
│   └── whisper-notes.page
├── ribbons/
│   ├── packet-process.ribbon
│   ├── cargo-setup.ribbon
│   └── whisper-call.ribbon
├── markers/
│   ├── me.marker
│   ├── packet-pilot.marker
│   ├── cargo-connect.marker
│   └── whisper-witness.marker
├── trails/
│   ├── packet-pilot.trail
│   ├── cargo-connect.trail
│   └── whisper-witness.trail
├── book.mark
├── mark.trail
└── mark.mstp
```

---

## 🤔 Why Bookmark?

This is not a `.mark`, `.book`, or `.page` generator — that’s what **MARK CLI** does.

Instead, Bookmark is:

* A Storybook-style interface for linking your **books**, **pages**, and **marks** to your own **marker** logic
* A runtime interface for building and following **marker flows**
* A shared environment where markers trigger agent actions or self-navigation
* A context-driven tool where adding a `.book`, `.page`, `.mark`, `.marker`, `.ribbon`, or `.trail` wires it into the system automatically

Just write your `.book`, `.page` and `.mark` files — and Bookmark will do the rest.

Note: **Trails** can be added to any `.mark` or `.marker` inside the `.bookmark/` to trail each use.

The system connects your books, pages, and marks together, creates a visual Bookmark interface, and dynamically builds markers, trails, ribbons, and MSTP records as you go.

---

## 💪 Usage

```
# Open a books interface
bookmark open <*.book>

# Open all book interfaces
bookmark open bookcase
```

---

## 📖 Example Use Cases

* Link `.mark` files together to create a `.marker` file
* Add `.ribbon` and `.trail` files to connect workflows and trails
* Watch your MSTP trail grow automatically as you work
* Run in dev, test, or production to see memory-based linking and flow in action

---

## 📜 License

MIT License — because memory belongs to everyone.

Use it. Fork it. Tell your story.

---

## 💬 Credits

Originally envisioned by **Jesse Conley**
Built to help truckers, builders, and humans remember who they are
Structured by the BookOS protocols and Storybook-style logic flow

> “Show me someone’s Book, and I’ll tell you who they are.”

---

**Jesse Edward Eugene Wayne Conley**

* 📬 [jesse.freightdev@gmail.com](mailto:jesse.freightdev@gmail.com)
* 🔗 [github.com/freightdev](https://github.com/freightdev)

> "I didn’t build this to automate the road. I built it so no one gets left behind."

---

## 💕 Support

If this project helps you or inspires your agent builds:
[Buy Me a Coffee](https://coff.ee/freightdev)

Every dollar goes toward tools for the ones still behind the wheel.

️ Jesse — [freightdev](https://github.com/freightdev)
