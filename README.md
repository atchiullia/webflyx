## 🎬 WebFlyx

**WebFlyx** is an imaginary self-hosted video streaming application created as part of a Git learning course. It demonstrates how content can be managed, updated, and delivered directly from a Git repository — no backend required!

---

### 📁 Project Structure

```
WebFlyx/
├── classics.csv         # Metadata about classic movies
├── contents.md          # Main content overview
├── titles.md            # List of available titles
├── quotes/
│   ├── dune.md
│   ├── starwars.md
│   └── titles.md        # Duplicate or alternative titles list
```

---

### 📚 Content Overview

* **`classics.csv`**
  A CSV file listing classic movies, possibly with release years, directors, and genres.

* **`contents.md`**
  A Markdown file outlining featured or available content in WebFlyx.

* **`titles.md` & `quotes/titles.md`**
  Lists of movie titles — may include active and archived versions.

* **`quotes/dune.md`**
  A curated set of quotes from *Dune*.

* **`quotes/starwars.md`**
  Quotes from *Star Wars*.

---

### 🧪 Purpose

This repo was built for **learning Git** — exploring concepts like:

* Version control of content files
* Branching, committing, and merging
* Handling multiple versions and backups (e.g., `quotes/`)
* Markdown editing and collaboration workflows

---

### 🛠 How to Use

You can clone the repo and explore it locally:

```bash
git clone https://github.com/atchiullia/WebFlyx.git
cd WebFlyx
```

View Markdown files in any editor or GitHub UI to simulate how content is served.

---

### 💡 Learning Highlights

* Practical Git operations: `add`, `commit`, `log`, `diff`, `merge`
* Managing structured (CSV) and unstructured (Markdown) content
* Organizing content with intent (main vs. bin/archive folders)

---

### 📄 License

MIT License – free to use, learn from, or expand upon.

