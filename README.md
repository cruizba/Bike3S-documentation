[![Build Status](https://travis-ci.org/cruizba/Bike3S-documentation.svg?branch=master)](https://travis-ci.org/cruizba/Bike3S-documentation)
# Bike3S-documentation
This repository contains a [mkdocs](https://www.mkdocs.org/) project static html page with the documentation referred to the project Bike3S (https://github.com/stimonm/Bike3S)

## Documentation site
https://cruizba.github.io/Bike3S-documentation/

---

## Edit and create html documentation with mkdocs

First of all you need to install mkdocs in your system. You can see how to install it [here](https://www.mkdocs.org/#manual-installation).

To edit the documentation and see results in real time in your browser insert the next commands:

1. Install material theme:
```
pip install mkdocs-material
```

2. Clone and serve the repository:
```
git clone https://github.com/cruizba/Bike3S-documentation.git
cd Bike3S-documentation
mkdocs serve
```

Open `http://127.0.0.1:8000/` in your browser and you will see a real time preview of your documentation.

To build the page insert the next commands:
```
mkdocs build
```

The site will be generated in the `site` folder in the documentation directory.

If you want to directly upload your page in the github repository:
```
mkdocs gh-deploy
```
After that you'll have your page available for everyone in

```
 https://<<username>>.github.io/Bike3S-documentation
```

where username is your github user name.

---

## Documentation structure

`mkdocs.yml` contains all the sections in documentation

`/docs` contains all the markdown files with documentation.





