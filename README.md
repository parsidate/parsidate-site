# ParsiDate Website

This is the official website for the [ParsiDate](https://github.com/parsidate/parsidate) project — a comprehensive Persian (Jalali/Shamsi) calendar library for Rust.

🌐 **Live site**: [https://parsidate.venv.ir](https://parsidate.venv.ir)

---

## 📦 About

This repository contains the source code and configuration for the ParsiDate website, built with [Zola](https://www.getzola.org/) and deployed via GitHub Pages.

It includes:

- Project overview and documentation
- Feature highlights and examples
- Links to crates.io, docs.rs, and source code
- Release and versioning info

---

## 🛠 Tech Stack

- **Static Site Generator**: [Zola](https://www.getzola.org/)
- **Theme**: [tabi](https://github.com/huhu/tabi)
- **Hosting**: GitHub Pages
- **Custom Domain**: [`parsidate.venv.ir`](https://parsidate.venv.ir)

---

## 🚀 Running Locally

Install [Zola](https://www.getzola.org/documentation/getting-started/installation/) first.

Then:

```bash
zola serve
```

Site will be available at [http://127.0.0.1:1111](http://127.0.0.1:1111)

To build the static site:

```bash
zola build
```

The output will be placed in the `public/` directory.

---

## 🌍 Deployment

We use GitHub Pages for deployment.

To deploy manually:

```bash
zola build
cd public
git init
git remote add origin git@github.com:parsidate/parsidate-site.git
git checkout -b gh-pages
git add .
git commit -m "Deploy site"
git push --force origin gh-pages
```

Make sure GitHub Pages is set to deploy from the `gh-pages` branch.

---

## 🧾 License

Content and code in this repo are licensed under the [Apache 2.0 License](./LICENSE).

---

## 🙌 Contributing

Found a typo? Want to improve something? PRs are welcome!
