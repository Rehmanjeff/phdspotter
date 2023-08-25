# PhD spotter Project

A scraping project using Scrapy and Django as the backend, of a ReactJS application

**NOTE:** This is a work in progress and is far from complete. We'll be
building out the frontend functionality for:

- Registration
- Login
- Logout
- View Upcoming Postions
- Filter Results
- Edit Profile

Once that's done we'll package this as a Django + React project.

## Requirements
```
Python 3.11
Node 18.17.1 (LTS)
```

## Installation

Clone the repo:

```
$ git clone git@github.com:rehmanjeff/phdspotter.git
```

Install the Python Requirements:

```
$ pip install -r requirements.txt
```

Then install the NPM Requirements (recommended use Node 4 - NVM is your friend):

```
$ npm install
```

## Running The Application

You should first build the assets with Webpack:

```
$ npm run build
```

You can also watch the files with:

```
$ npm run watch
```

Once built, you can run the Django dev server:

```
$ django runserver
```

Now you can access the application at `http://127.0.0.1:8000`
