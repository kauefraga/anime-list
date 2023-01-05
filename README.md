<div align="center">
  <h1><code>Anime List</code></h1>

  <p>
    <strong>📖 A list to save all my viewed animes 📖</strong>
  </p>

  <p>
    <img
      alt="GitHub top language"
      src="https://img.shields.io/github/languages/top/kauefraga/anime-list.svg"
    />
    <img
      alt="Repository size"
      src="https://img.shields.io/github/repo-size/kauefraga/anime-list.svg"
    />
    <a href="https://github.com/kauefraga/anime-list/commits/main">
      <img
        alt="GitHub last commit"
        src="https://img.shields.io/github/last-commit/kauefraga/anime-list.svg"
      />
    </a>
    <img
      alt="GitHub LICENSE"
      src="https://img.shields.io/github/license/kauefraga/anime-list.svg"
    />
  </p>
</div>

## ✨ Features

- **Fancy UI**: A minimal UI that exposes everything you need
- **Colorized Outputs**: Everything looks better with some colors
- **Nice help**: If you need some help, just use the flag `--help`
- **Commands**:
  - `list`: query and show all the saved animes
  - `save`: create an anime with a given title/description and save it
  - `open`: search for an anime with a title and return it with a url

## ⬇️ How to install and use it

```bash
git clone https://github.com/kauefraga/anime-list.git
cd anime-list

pip install -r requirements.txt
python3 src/main.py COMMAND
```
You are welcome to open issues and pull requests!

## 💻 Technologies

- 🐍 [Python](https://www.python.org) - A programming language that lets you work quickly
and integrate systems more effectively.
- 🕶 [Click](https://pypi.org/project/click) - Composable command line interface toolkit
- 🗃 [Peewee](https://pypi.org/project/peewee) - Peewee is a simple and small ORM.
- 🎨 [Rich](https://pypi.org/project/rich) - Rich is a Python library for rich text and beautiful formatting in the terminal.
- 🛡 [Validators](https://pypi.org/project/validators) - A library for validating URLs
- 💾 [Sqlite](https://www.sqlite.org/index.html) - A small, fast, self-contained... A SQL database engine

## 📜 Coming soon...

- `list`: add visual feedback
- `list`: the database will grow, therefore query and print only today animes
- `list`: query and write to a file (-o --output)
- `list`: query all the animes and display it (-a --all)
- `open`: show a list of nice websites (-a --all)
- `open`: if some anime does not exists, display something like: "did you mean {an existing anime}?"

## 📝 License

This project is licensed under the MIT License - See the [LICENSE](https://github.com/kauefraga/anime-list/blob/main/LICENSE) for more information.

---

<div align="center" display="flex">
  <img alt="Built with love" src="https://forthebadge.com/images/badges/built-with-love.svg">
  <img alt="Powered by coffee" src="https://forthebadge.com/images/badges/powered-by-coffee.svg">
</div>
