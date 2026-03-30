# WordFlow

**WordFlow** is an experimental open-source editor that rethinks how documents are created, structured, and stored.

It is usable directly from the web and runs as a lightweight, browser-based application.

👉 Live demo: **https://jonastech25-cmyk.github.io/Word-Flow/**

Instead of hiding structure behind a visual-only editor, WordFlow exposes the full document model in real time using a custom JSON-based format (`.wfd`), giving users full control over content, layout, and transformations.

---

## ✨ Core Concept

WordFlow treats documents as **structured data, not plain text**.

Every change in the editor directly modifies the underlying JSON representation, making the document fully transparent and programmable.

---

## 🚀 Current Features (Implemented)

* 🌐 **Web-based editor**
  Fully usable in the browser, no installation required.

* 🔄 **Live JSON structure view**
  Real-time synchronization between editor and `.wfd` document model.

* 🧱 **Block-based document system**
  Content is organized into structured blocks (heading, paragraph, etc.).

* 📄 **Custom file format (.wfd)**
  A lightweight JSON-based format designed for extensibility.

* 📤 **Export system**
  Export documents to:

  * HTML
  * Markdown
  * Plain text

* ⚡ **Lightweight architecture**
  Minimal overhead, focused on speed and simplicity.

---

## 🧪 Example `.wfd` Structure

```json id="n9p1ka"
{
  "version": 1,
  "type": "wfd",
  "title": "Example Document",
  "blocks": [
    {
      "type": "heading",
      "level": 1,
      "content": "Hello World"
    },
    {
      "type": "paragraph",
      "content": "This is a simple paragraph."
    }
  ]
}
```

---

## 🧠 Philosophy

Most modern editors prioritize UI abstraction and hide internal structure.

WordFlow does the opposite:

* The document structure is always visible
* The user has full control over the data model
* Content becomes programmable and transformable

---

## 🧩 Planned Features (Roadmap)

* 🧩 **Plugin system**
  Extend editor functionality with custom blocks and tools.

* 🤝 **Collaboration mode**
  Real-time multi-user editing.

* 🧱 **Advanced block types**
  Tables, embeds, media blocks, and custom components.

* 📥 **Import system**
  Support for Markdown, HTML, and external formats.

* 🎨 **UI/UX redesign**
  More polished and user-friendly interface.

---

## 🤖 AI Integration (Planned / Experimental)

A future goal of WordFlow is to integrate AI capabilities directly into the editor.

Possible directions include:

* Local LLM support (privacy-focused, offline usage)
* AI-assisted writing inside blocks
* Automatic structuring of raw text into `.wfd` format
* Context-aware suggestions based on document structure

The idea is to allow WordFlow to run with **local models (LLMs)** for full offline AI-assisted editing.

---

## 🧪 Status

⚠️ This project is currently in **early experimental stage**

Expect:

* breaking changes
* incomplete features
* active development and redesigns

---

## 🤝 Contributing

Contributions, ideas, and feedback are welcome.

You can contribute by:

* Opening issues
* Suggesting features
* Submitting pull requests

---

## 📜 License

This project is licensed under the **GNU GPL v3**.

---

## 🔥 Why WordFlow?

Because traditional editors treat documents as text.

WordFlow treats them as **structured, interactive data**.
