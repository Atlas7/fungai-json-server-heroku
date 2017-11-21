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

Start `json-server` where a fake API is served. Essentially an entire toy database (that I created) in one `db.json`.

```
npm run start
```

This will start a fake API at [http://localhost:3000](http://localhost:3000).

Run test:

```
npm run test
```

This will run Mocha tests.