<h1 align="center"><b> 📚 Developer Resources </b></h1>

<br>

**Page** | **Content**
-- | --
[Software Development](docs/pages/software_development.md) | Links to Python, Java, Scala, R, Git, CLI, RegEx and many other resources
[Apache](docs/languages/apache.md) | Links to Apache tooling
[JVM](docs/languages/jvm.md) | Guides for learning JVM languages
[Python](docs/languages/python.md) | Python study resources
[Rstats](docs/languages/rstats.md) | Intro / adv. R materials
[Rust](docs/languages/rust.md) | Learning resources for Rust
[SQL](docs/languages/sql.md) | SQL & database resources
[Azure](docs/cloud/azure.md) | Azure cloud blogs, links and tools
[Data Engineering](docs/pages/data_engineering.md) | Links to resources to learn Data & Analytics Engineering tools, methods and worlflows
[Machine Learning](docs/pages/machine_learning.md) | Links to resources for learning data analytics, data science and machine learning
[Data Sources](docs/pages/data_cave.md) | API & dataset resources grouped by topic
[Cheat Sheet Library](docs/pages/cheat_sheets.md) | A range of cheat sheets for Python, SQL, Data Science & Visual Studio Code


This project has been build using mkdocs & the mkdocs-material theme.

- The site is configured using the [mkdocs.yml](/mkdocs.yml)

- Site pages are managed via the [docs](/docs/) directory

- Build is managed via [GitHub Actions](https://github.com/DNYFZR/Resources/actions)

<br>

Python has been used to create a development environment, and to install the mkdocs packages within it :

````ps1
# Set up & install
python -m venv <env_name>
cd <env_name>/scripts
./activate

python -m pip install -U pip
python -m pip install mkdocs mkdocs-material

# Setup project
cd ../../
mkdocs new <project_name>

# Launch mkdocs local server 
cd <project_name>
mkdocs serve

````
