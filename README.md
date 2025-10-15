# 💼 Jekyll Portfolio Template

A clean, single-page Jekyll portfolio template — perfect for the **lazy student, busy researcher, or anyone** who wants a nice-looking academic or personal page without too much effort.  
It uses **Tailwind CSS via CDN**, **Bootstrap Icons**, and **Academicons** to make links and buttons look neat straight out of the box.

👉 See the live demo [**here**](https://di-unipi.github.io/portfolio-template/).

---

## ⚙️ Requirements
- [**Ruby**](https://www.ruby-lang.org/en/documentation/installation/) (version ≥ 3 recommended)  
- [**Bundler**](https://bundler.io/) (`gem install bundler`, after Ruby is installed)

---

## 📦 Installing dependencies
```bash
make install
```

## 🧑‍💻 Local development
```bash
make serve
# then open http://localhost:4000
```

## 🚀 Production build
```bash
make build
# output will be generated in ./_site
```

## 🧾 Filling in your data
All editable content lives inside the `_data/` folder.
You only need to edit three files to make the whole site yours:
 - `_data/author.yaml` → your personal details: name, role, affiliation, contacts, social links, address, and short bio.
 - `_data/experience.yaml` → your timeline: split into education and work, each with title, institution, period, and description.
 - `_data/publications.yaml` → your research outputs: list of publications with title, authors, venue, year, and optional links (PDF, DOI, code, etc.).

🪶 Leave any field empty to hide it.

📄 Sections automatically disappear when their corresponding data files are empty.

## 🌍 Publishing
- Use GitHub Actions to run `make build` and automatically deploy the `_site` folder.
- You can also request free web hosting for your research page on the **[pages.di.unipi.it](https://pages.di.unipi.it)** server. Simply send an email to **help.polo2@sid.unipi.it** asking for access and they'll help you set it up.
