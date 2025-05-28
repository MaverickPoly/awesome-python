# Awesome Python

A curated list of awesome Python frameworks, libraries, software, and resources, focusing on modern, actively maintained projects across various domains.

## Contents

* [Web Development](#web-development)
    * [Frameworks](#web-frameworks)
    * [HTTP Clients](#http-clients)
    * [Web Scraping](#web-scraping)
    * [APIs & REST](#apis--rest)
* [Data Science & Machine Learning](#data-science--machine-learning)
    * [Numerical & Data Manipulation](#numerical--data-manipulation)
    * [Machine Learning & Deep Learning](#machine-learning--deep-learning)
    * [Data Visualization](#data-visualization)
    * [Natural Language Processing (NLP)](#natural-language-processing-nlp)
* [Desktop GUI Development](#desktop-gui-development)
* [Game Development](#game-development)
* [Cybersecurity & Networking](#cybersecurity--networking)
* [Automation & Scripting](#automation--scripting)
* [Databases](#databases)
* [Testing](#testing)
* [Development Tools](#development-tools)
    * [Code Quality & Formatting](#code-quality--formatting)
    * [Environment Management](#environment-management)
    * [Command-Line Tools](#command-line-tools)
* [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)
* [Learning Resources](#learning-resources)
* [Awesome Resources](#awesome-resources)
* [Contributing](#contributing)
* [License](#license)

---

## Web Development

### Frameworks

* **[Django](https://www.djangoproject.com/)**: The web framework for perfectionists with deadlines. Known for its "batteries-included" approach, suitable for complex, database-driven websites.
* **[Flask](https://flask.palletsprojects.com/)**: A lightweight WSGI web application framework. Designed to make getting started quick and easy, with the ability to scale up to complex applications.
* **[FastAPI](https://fastapi.tiangolo.com/)**: A modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints. Great for robust and production-ready APIs.
* **[Pyramid](https://trypyramid.com/)**: A minimalist, flexible, and powerful web framework. It scales from a small application to a large one, and offers a lot of freedom in terms of structure.
* **[Tornado](https://www.tornadoweb.org/en/stable/)**: A Python web framework and asynchronous networking library, originally developed for FriendFeed. Ideal for long polling, WebSockets, and other applications that require a long-lived connection to each user.

### HTTP Clients

* **[Requests](https://requests.readthedocs.io/en/latest/)**: The de facto standard for making HTTP requests in Python. Simple, elegant, and powerful.
* **[HTTPX](https://www.python-httpx.org/)**: A fully featured HTTP client for Python 3, which provides sync and async APIs, and support for HTTP/1.1 and HTTP/2.

### Web Scraping

* **[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)**: A library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree.
* **[Scrapy](https://scrapy.org/)**: An open-source and collaborative framework for extracting the data you need from websites.
* **[Selenium](https://www.selenium.dev/)**: Automates web browsers. Primarily used for testing, but also great for web scraping requiring JavaScript rendering.

### APIs & REST

* **[Django REST Framework](https://www.django-rest-framework.org/)**: A powerful and flexible toolkit for building Web APIs.
* **[Pydantic](https://docs.pydantic.dev/latest/)**: Data validation and settings management using Python type hints. Essential for FastAPI and other API validation.

## Data Science & Machine Learning

### Numerical & Data Manipulation

* **[NumPy](https://numpy.org/)**: The fundamental package for numerical computing with Python. Provides powerful N-dimensional array objects and functions.
* **[Pandas](https://pandas.pydata.org/)**: A fast, powerful, flexible, and easy-to-use open-source data analysis and manipulation tool, built on top of the Python programming language.
* **[SciPy](https://scipy.org/)**: A collection of open-source software for mathematics, science, and engineering. Builds on NumPy.
* **[Dask](https://docs.dask.org/en/latest/)**: A flexible library for parallel computing and handling larger-than-memory datasets. Integrates with NumPy and Pandas.
* **[Polars](https://pola.rs/)**: A blazing-fast DataFrames library written in Rust, with bindings for Python. Designed for performance and large datasets.

### Machine Learning & Deep Learning

* **[Scikit-learn](https://scikit-learn.org/stable/)**: A simple and efficient tool for data mining and data analysis. Built on NumPy, SciPy, and Matplotlib, covering various classification, regression, and clustering algorithms.
* **[TensorFlow](https://www.tensorflow.org/)**: An open-source machine learning framework developed by Google. Used for building and training neural networks.
* **[PyTorch](https://pytorch.org/)**: An open-source machine learning library developed by Facebook AI Research (FAIR). Known for its flexibility and ease of use in deep learning research.
* **[Keras](https://keras.io/)**: A high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. Simplifies deep learning model creation.
* **[XGBoost](https://xgboost.readthedocs.io/en/stable/)**: An optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.
* **[LightGBM](https://lightgbm.readthedocs.io/en/latest/)**: A gradient boosting framework that uses tree-based learning algorithms. Designed for speed and high performance.

### Data Visualization

* **[Matplotlib](https://matplotlib.org/)**: A comprehensive library for creating static, animated, and interactive visualizations in Python.
* **[Seaborn](https://seaborn.pydata.org/)**: A Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
* **[Plotly](https://plotly.com/python/)**: An interactive, open-source graphing library that supports over 40 unique chart types, including 3D charts, statistical graphs, and financial charts.
* **[Dash](https://dash.plotly.com/)**: A productive Python framework for building analytical web applications. No JavaScript required.
* **[Altair](https://altair-viz.github.io/)**: A declarative statistical visualization library for Python, based on Vega-Lite.

### Natural Language Processing (NLP)

* **[NLTK](https://www.nltk.org/)**: The Natural Language Toolkit, a leading platform for building Python programs to work with human language data.
* **[spaCy](https://spacy.io/)**: An industrial-strength natural language processing (NLP) library designed to be fast and efficient for production use.
* **[Hugging Face Transformers](https://huggingface.co/docs/transformers/index)**: Provides thousands of pre-trained models to perform tasks on texts, such as classification, information extraction, summarization, translation, text generation, and more.

## Desktop GUI Development

* **[PyQt](https://www.riverbankcomputing.com/software/pyqt/intro)**: A set of Python bindings for the Qt application framework. Enables creation of rich graphical user interfaces.
* **[Tkinter](https://docs.python.org/3/library/tkinter.html)**: Python's standard GUI (Graphical User Interface) toolkit. It's simple and built-in, making it good for smaller applications or learning.
* **[Kivy](https://kivy.org/)**: An open-source Python library for rapid development of applications that make use of innovative user interfaces, such as multi-touch apps. Cross-platform, including mobile.
* **[PySide6](https://doc.qt.io/qtforpython/index.html)**: The official Python bindings for Qt, offering a permissive LGPL license compared to PyQt's GPL.
* **[PySimpleGUI](http://www.pysimplegui.org/)**: A wrapper around Tkinter, Qt, WxPython, and Remi, designed to make GUI development extremely easy for beginners.

## Game Development

* **[Pygame](https://www.pygame.org/)**: A set of Python modules designed for writing video games. It includes computer graphics and sound libraries designed to be used with the Python programming language. Excellent for 2D games and learning game dev basics.
* **[Arcade](https://arcade.academy/)**: An easy-to-use Python library for creating 2D arcade games with an emphasis on simple, object-oriented design. Built on top of Pygame and Pyglet.
* **[Pyglet](https://pyglet.readthedocs.io/en/latest/)**: A powerful, easy-to-use Python library for developing games and other visually rich applications. Supports windowing, user interface events, Joysticks, OpenGL graphics, loading images and videos, and playing sounds and music.
* **[Panda3D](https://www.panda3d.org/)**: An open-source, cross-platform 3D engine written in C++, with a complete set of Python bindings. Used for games, simulations, and visualizations.
* **[Ren'Py](https://www.renpy.org/)**: A visual novel engine that helps you make interactive stories and games. It's written in Python and can create multi-platform games.
* **[Raylib](https://pypi.org/project/raylib/)**: A low-level library for 2D and 3D programming, built in C. It provides a simple API for creating windows, rendering, handling user input, and more.


## Automation & Scripting

* **[Selenium](https://selenium-python.readthedocs.io/)**: Python bindings for the Selenium WebDriver, used for automating web browser interaction for testing, data scraping, and more.
* **[Fabric](http://www.fabfile.org/)**: A high-level Python library designed to streamline the use of SSH for application deployment or systems administration tasks.
* **[Ansible](https://www.ansible.com/)**: An open-source automation tool, for configuration management, application deployment, orchestrating more advanced tasks. Uses Python on the control node.
* **[OpenPyXL](https://openpyxl.readthedocs.io/en/stable/)**: A Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files. Useful for automating spreadsheet tasks.
* **[python-docx](https://python-docx.readthedocs.io/en/latest/)**: A Python library for creating and updating Microsoft Word .docx files.
* **[PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)**: A cross-platform GUI automation Python module for human beings. Lets your Python scripts control the mouse and keyboard, and interact with other applications.
* **[Schedule](https://schedule.readthedocs.io/en/stable/)**: A simple, lightweight, in-process scheduler for jobs.

## Cybersecurity & Networking

* **[Scapy](https://scapy.net/)**: A powerful interactive packet manipulation program. It can forge or decode packets of a wide number of protocols, send them on the wire, capture them, match requests and replies, and much more.
* **[Paramiko](https://www.paramiko.org/)**: A Python implementation of the SSHv2 protocol, providing both client and server functionality. Useful for automating remote command execution and file transfers.
* **[Python-Nmap](https://pypi.org/project/python-nmap/)**: A Python library that helps in using the Nmap port scanner.
* **[Cryptography](https://cryptography.io/en/latest/)**: A package that provides cryptographic recipes and primitives to Python developers. Includes both high-level recipes and low-level interfaces to common cryptographic algorithms.
* **[Impacket](https://github.com/SecureAuthCorp/impacket)**: A collection of Python classes for working with network protocols. It's a key tool for penetration testers.

## Databases

* **[SQLAlchemy](https://www.sqlalchemy.org/)**: The Python SQL toolkit and Object Relational Mapper that gives developers the full power of SQL. Supports various databases.
* **[Psycopg2](https://www.psycopg.org/docs/)**: The most popular PostgreSQL adapter for the Python programming language.
* **[PyMySQL](https://pymysql.readthedocs.io/en/latest/)**: A pure Python MySQL client library.
* **[sqlite3](https://docs.python.org/3/library/sqlite3.html)**: Python's built-in module for working with SQLite databases.
* **[Redis-Py](https://redis-py.readthedocs.io/en/stable/)**: The Python client for the Redis key-value store.
* **[Pymongo](https://pymongo.readthedocs.io/en/stable/)**: The official MongoDB driver for Python.

## Testing

* **[Pytest](https://docs.pytest.org/en/stable/)**: A mature full-featured Python testing framework that helps you write better programs. Known for its simplicity and extensibility.
* **[unittest](https://docs.python.org/3/library/unittest/index.html)**: Python's built-in unit testing framework, inspired by JUnit.
* **[Mock](https://docs.python.org/3/library/unittest.mock.html)**: A library for mocking or patching parts of your code during tests (built into `unittest` in Python 3.3+).
* **[Coverage.py](https://coverage.readthedocs.io/en/latest/)**: Measures code coverage, typically during test execution.
* **[Factory Boy](https://factoryboy.readthedocs.io/en/stable/)**: A fixtures replacement for Python, used for generating fake data for tests.
* **[PyHamcrest](https://pyhamcrest.readthedocs.io/en/latest/)**: A framework for writing matcher objects, allowing you to create flexible assertions in your tests.

## Development Tools

### Code Quality & Formatting

* **[Black](https://github.com/psf/black)**: The uncompromising Python code formatter. Formats code consistently without manual intervention.
* **[Flake8](https://flake8.pycqa.org/en/latest/)**: A wrapper around PyFlakes, pycodestyle and McCabe. A great tool for enforcing style guidelines and catching common errors.
* **[isort](https://pycqa.github.io/isort/)**: A Python utility/library to sort imports alphabetically, and automatically separated into sections and by type.
* **[Pylint](https://www.pylint.org/)**: A static code analyzer that checks for errors in Python code, tries to enforce a coding standard, and looks for code smells.
* **[mypy](https://mypy-lang.org/)**: An optional static type checker for Python that aims to combine the benefits of dynamic and static typing.

### Environment Management

* **[venv](https://docs.python.org/3/library/venv.html)**: Python's built-in module for creating lightweight virtual environments.
* **[Poetry](https://python-poetry.org/)**: A tool for dependency management and packaging in Python. Simplifies project setup, virtual environments, and publishing.
* **[Conda](https://docs.conda.io/en/latest/)**: An open-source package management system and environment management system. Widely used in the data science community for managing complex dependencies.
* **[Pipenv](https://pipenv.pypa.io/en/latest/)**: A tool that aims to bring the best of all packaging worlds to the Python world (bundler, composer, npm, cargo, yarn, etc.).

### Command-Line Tools

* **[Click](https://click.palletsprojects.com/en/latest/)**: A Python package for creating beautiful command line interfaces in a composable way with as little code as necessary.
* **[Typer](https://typer.tiangolo.com/)**: A library for building CLI applications that is based on Python type hints and inspired by FastAPI.
* **[Rich](https://rich.readthedocs.io/en/stable/)**: A Python library for rich text and beautiful formatting in the terminal.
* **[Asciinema](https://asciinema.org/)**: A free and open-source solution for recording terminal sessions and sharing them on the web.

## Integrated Development Environments (IDEs)

* **[PyCharm](https://www.jetbrains.com/pycharm/)**: A powerful and popular IDE by JetBrains specifically designed for Python development. Offers Community (free) and Professional editions.
* **[VS Code](https://code.visualstudio.com/)**: A lightweight, but powerful source code editor that runs on your desktop. Its rich ecosystem of extensions, especially the official Python extension, makes it an excellent choice for Python.
* **[Jupyter Notebook / JupyterLab](https://jupyter.org/)**: An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. Essential for data science.
* **[Spyder](https://www.spyder-ide.org/)**: An open-source scientific Python IDE, popular among data scientists, with features like variable explorer, debugger, and profiler.
* **[Sublime Text](https://www.sublimetext.com/)**: Sophisticated text and code editor that is popular among developers and writers for its speed, versatility, and customizable features.
* **[Vim / NeoVim](https://neovim.io/)**: A highly configurable text editor that can be extended with plugins to become a powerful Python development environment.

## Learning Resources

* **[Python Official Documentation](https://docs.python.org/3/)**: The comprehensive and authoritative source for all things Python.
* **[Real Python](https://realpython.com/)**: High-quality Python tutorials and courses for all skill levels, covering a wide range of topics.
* **[Python for Everybody](https://www.py4e.com/)**: A series of free courses and books by Dr. Charles Severance for learning Python. Great for beginners.
* **[Google's Python Class](https://developers.google.com/edu/python)**: A free class for people with a little programming experience who want to learn Python. Includes lectures, written materials, and coding exercises.
* **[Codecademy Python Track](https://www.codecademy.com/learn/learn-python-3)**: Interactive online courses to learn Python programming from scratch.
* **[TestDriven.io](https://testdriven.io/)**: High-quality tutorials on Django, Flask, FastAPI, Docker, and more, focusing on practical, test-driven development.

## Awesome Resources

* **[PyPI (Python Package Index)](https://pypi.org/)**: The official third-party software repository for Python, where you can find thousands of packages.
* **[Python.org](https://www.python.org/)**: The official website of the Python programming language, including downloads, documentation, and news.
* **[Python Software Foundation (PSF)](https://www.python.org/psf/)**: The non-profit organization behind Python, supporting the language and its community globally.
* **[Stack Overflow (Python Tag)](https://stackoverflow.com/questions/tagged/python)**: A comprehensive Q&A site for programmers, with a very active Python community for seeking and offering help.
* **[Python Reddit (r/Python)](https://www.reddit.com/r/Python/)**: A popular community on Reddit for Python news, discussions, and help, covering a wide range of topics.
* **[Planet Python](https://planetpython.org/)**: An aggregator of Python blogs and news feeds from around the world, providing a centralized view of new content.
* **[Python Weekly Newsletter](https://www.pythonweekly.com/)**: A free weekly newsletter featuring curated Python articles, projects, and news delivered to your inbox.
* **[Talk Python To Me Podcast](https://talkpython.fm/)**: A weekly podcast on Python and related technologies, featuring interviews with prominent community members and discussions on various topics.
* **[Python Bytes Podcast](https://pythonbytes.fm/)**: A short, digestible weekly podcast discussing the latest Python news and packages, ideal for staying up-to-date.
* **[PyCon US](https://us.pycon.org/)**: The largest annual gathering for the Python community in the United States, featuring talks, tutorials, and sprints.
* **[EuroPython](https://ep2024.europython.eu/)**: The largest annual Python conference in Europe, bringing together developers from across the continent and beyond.
* **[PyData](https://pydata.org/)**: A series of conferences focused on the use of Python in data science, including workshops and networking opportunities.
* **[GitHub (Python Language Filter)](https://github.com/topics/python)**: The primary platform for hosting open-source Python projects, discoverable via language topics and a great place to find new libraries and contribute.
* **[Awesome Python (vinta/awesome-python)](https://github.com/vinta/awesome-python)**: The original, most comprehensive, and widely used 'awesome' list for Python. An excellent resource for further exploration and discovering niche projects.

---

## Contributing

Contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) to ensure your suggestions are added smoothly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.