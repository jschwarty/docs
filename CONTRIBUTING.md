# Contributing

From opening a bug report to creating a pull request: every contribution is
appreciated and welcome. If you're planning to implement a new section or page 
please create an issue first. This way we can ensure that your precious
work is not in vain.

## Setup

* Install [Node.js](https://nodejs.org/) if you have not already
* Fork the **webpack docs** repo at [https://github.com/webpack/docs](https://github.com/webpack/docs).
* `git clone <your-clone-url> && cd docs`
* `npm install`
* `npm start`
* Visit [http://localhost:8088](http://localhost:8088) to preview your changes before making a pull request.

## Branching Your Changes

Making a branch in your fork for you contribution is helpful in the following ways:  
* It allows you to have multiple contributions in as PRs at once.
* When you create a PR the subject will auto-fill with the branch name.

### Naming Branches

Let's say you are adding a `CHANGELOG.md` file to the rep. Your branch 
could have the name:
```
add-changelog-file
```

And let's say you are updating the API configuration page to remove the `watch`
option documentation your branch could have the name:
```
remove-watch-from-api-configuration
```

## Submitting Changes

After getting some feedback, push to your fork branch and submit a pull request. We
may suggest some changes or improvements or alternatives, but for small changes
your pull request should be accepted quickly.

## Thank you!

Webpack is insanely feature rich and documentation is a huge time sink. We
greatly appreciate any time spent fixing typos or clarifying sections in the
documentation.