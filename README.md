# Deployed API

We've deployed the API to Heroku at:

[https://fungai-json-server-heroku.herokuapp.com/](https://fungai-json-server-heroku.herokuapp.com/)

# Development Instruction

To run this app locally on a macbook / laptop do the followings:

Clone this repository to an appropriate location on your machine:

```
git clone https://github.com/Atlas7/fungai-json-server-heroku.git
```

Install NPM dependencies:

```
npm install
```

Start `json-server` where a fake API is served. Essentially an entire toy database (that we created) in one `db.json`.

```
npm run start
```

This will start a fake API at [http://localhost:3000](http://localhost:3000).

Run test:

```
npm run test
```

This will run Mocha tests.

# Deploy to Heroku

Use [this really handy guide](https://github.com/Atlas7/json-server-heroku) for tips on deploying to heroku.
This is a fork to [this original GitHub repository](https://github.com/jesperorb/json-server-heroku).

# Realated Apps that consume this API

- [fungai-react-ui](https://github.com/Atlas7/fungai-react-ui): a ReactJS UI prototype for fungai.org (work in progress)
- etc.
