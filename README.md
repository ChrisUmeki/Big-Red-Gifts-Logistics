# Big Red Gifts - Logistics subteam (Oct 2017 - Dec 2017)
Logistic related tools for https://bigred.gifts, a campus-wide gift exchange organized by Creative Computing Club at Cornell University. Commit history has kept in private repo to avoid sharing various student data.
### Team Members
* Valeriya Rusina '20  
* Wilona Shen '20  
* Chris Umeki '19  
* Mena Wang '20
### Running
Before installing, have [Node.js](https://nodejs.org/en/download/).

Install dependencies with
```bash
$ npm install
```
Run

```bash
$ npm run-script label
```

```bash
$ npm run-script matchemail
```

```bash
$ npm run-script eventreminder
```

Database information stored in the sqlite with following schema

```sqlite
CREATE TABLE info(id INTEGER PRIMARY KEY AUTOINCREMENT,
    first_name TEXT, last_name TEXT, year INT, netId TEXT, gender TEXT, bio TEXT,
    gift1 TEXT, gift2 TEXT, gift3 TEXT,
    price_range TEXT,
    ex_type TEXT, address TEXT, off_campus INT, match_id TEXT);
```

![Big Red Gifts Logo](https://bigred.gifts/images/logo.png)
