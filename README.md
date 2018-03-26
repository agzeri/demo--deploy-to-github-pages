# Deploy to GitHub Pages

**We need a basic website with `index.html`, `styles.css` and `main.js`.<br />
The purpose of this is to see how all parts are interacting in a production site.**

### Steps

+ Create a local project from this [pen](https://codepen.io/agzeri/pen/aYoVxX).
_This is a prefect example because we are consuming an API with JavaScript and printing all results in HTML. We added styles with CSS._

#### Recommend Structure

```
- api-characters
|
|---index.html
|
|---/css
|   |
|   |---styles.css
|
|---/scripts
|   |
|   |---main.js
```

### Using `git` to setup the local project

#### Setup `git` in local project.

+ Create a repo in your GitHub account.
+ Link local project to `GitHub`, follow the steps that appears when you create a repo.

### Deploy to GitHub pages

+ Create a branch with next command, and name it `gh-pages`. **Pay attention to the branch name, it should be equal.**

###### Command to create any branch.
```sh
$ git checkout -b «branch-name»
```

###### Create a `gh-pages` branch in local project
```sh
$ git checkout -b gh-pages
```

+ Push the whole work to `gh-pages` branch. **Your work should be commited before pushing.**
```sh
$ git push origin gh-pages
```

+ Check your repo on `GitHub`, and try to find `gh-pages`, is everything is there you are good to go.

+ Go to `username.github.io/project-name` in browser, now you’ll se your project online and alive. <br /> You can share that URL to the world.
