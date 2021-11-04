# Advanced Python Course 2021

## Lecture 1 Oct. 26th:

* Gabor explained about the process of cloning, sending a push and a pull request.
* git status
* git diff
* git add .
* git commit -m "comment"
* git log - shows the logs of the commits
* git push


### [Testing](https://code-maven.com/slides/python/testing-demo)

* [doctest](https://code-maven.com/slides/python/testing-demo-doctest)
* [unitest](https://code-maven.com/slides/python/testing-demo-unittest) - the example was with a Class, object oriented, which we do not need to write in the course
* [pytest](https://code-maven.com/slides/python/testing-demo-pytest) need to install

### HW:

- [x] Send a pull request with notes and json with personal details
- [x] 10 exercises on exercism with mentoring

## Lecture 2 Nov. 2nd:

* We learned how to create a GitHub page using Markdown.
* We went over the following:
```
git init                     # create local repository

git status
git diff
git add <FILENAME>           # add to stage
git reset HEAD <FILENAME>    # remove from stage, unstage
git commit -m "some message"
git restore <FILENAME>       # forget the local, not yet committed, changes.
git checkout <FILENAME>      # the same as "restore" for older versions of git.
git log                      # to see the history of changes.
.gitignore                   # to avoid adding unwanted files.
```

```
git rm                       # to remove a file from git. However, remember the file will remain in the history.
git mv                       # To move or rename a file and let git record this change.
```

```
git push

git clone
git pull
```
### HTML
Titles and paragraphs:
```
<h1>Hello world</h1>                                   #big title (there are h1... h6)
<p>text</p>                                            #for each new paragraph
```
Lists:
```
<ul>                                                   #unordered list with bullets
	<li>one</li>
	<li>two</li>
</ul>
<hr>                                                   #horizontal line
<ol>                                                   #ordered list with numbers
	<li>one</li>
	<li>two</li>
</ol>
```

Table:
```
<table>                                                #table
	<tr><th>Name</th><th>Phone></th></tr>
	<tr><td>Rotem</td><td>0525437632></td></tr>
	<tr><td>Another name</td><td>Another number></td></tr>
</table>
```
Links:
```
<a href="https://...">Name to be linked</a>
```

* We can change the small logo on the tab. It's called favicon.

### HW:

- [x] Create a GitHub repository named RotemShalita.github.io. Use Markdown to create your website. Write your notes of the course in a Markdown file, and add a Markdown page to all the exercises completed on exercism. Also use a theme.
- [x] Create another Github repo that will be used to create HTML-based web site. Create the `docs/` directory and an `index.html` file in it. In the **Settings** you'll find an entry for **Pages** where you can tell which branch to use (main) and what directory to serve (docs).


