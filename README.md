# Table of Contents
1. [HTML](#html)
2. [CSS](#css)
3. [Bootstrap](#bootstrap)
4. [Git](#bootstrap)

<a name="html"></a>
# HTML 
## HTML Setup
```
<!DOCTYPE html>
<html>
  <head>
    <!--Metadata (ex.: Styles, Scripts importing libraries like Bootstrap, etc.) goes here-->
    
  </head>
  <body>
    <!--Main content goes here-->
    
  </body>
</html>
```

## HTML Tags
| Tag    | Description    | Renders as |
| ---    | -----------    | -------    |
| `<tag>[TEXT]</tag>` | This is a paragraph | <p>[TEXT]</p> |
| `<h1>[Text]</h1>` | This is the largest heading size | <h1>[Text]</h1> |
| `<h2>[Text]</h2>` | This is the second-largest heading size | <h2>[Text]</h2> |
| `<h3>[Text]</h3>` | This is the third-largest heading size | <h3>[Text]</h3> |
| `<h4>[Text]</h4>` | This is the fourth-largest heading size | <h4>[Text]</h4> |
| `<h5>[Text]</h5>` | This is the fifth-largest heading size | <h5>[Text]</h5> |
| `<h6>[Text]</h6>` | This is the sixth-largest heading size | <h6>[Text]</h6> |
| `<a href=”[URL]”>[Text]</a>` | Link to specific URL | <a href=”[URL]”>[Text]</a> |
| `<div>[content]</div>` | Divider | <div>[content]</div> |
| `<!-- Comment -->` | Adding comments | <!-- Comment --> *doesn't appear* |
| `<img src= "[URL or local file path]">` | Adding images | <img src= "https://se-images.campuslabs.com/clink/images/b756bfe9-96e6-4d0f-89b1-1b163fcd7b73a31a4e58-57c6-4b2e-ac30-07c70fe14d8d.png?preset=med-sq"> |
| `<table><tr><th>[Content]</th><td>[Content]</td></tr></table>` | Adding a Table | <table><tr><th>[Content]</th><td>[Content]</td></tr></table> |
| `<ul><li>[Content]</li></ul></code>` | Unordered List | <ul><li>[Content]</li></ul> |
| `<ol><li>[Content]</li></ol>` | Ordered List | <ol><li>[Content]</li></ol> |
| `<u>[Text]</u>` | Underline | <u>[Text]</u> |
| `<em>[Text]</em>` | Italics | <em>[Text]</em> |
| `<strong>[Text]</strong>` | Bold | <strong>[Text]</strong> |
| `<header>[Content]</header>` | Header | <header>[Content]</header> |
| `<nav>[Content]</nav>` | Navigation | <nav>[Content]</nav> |
| `<main>[Content]</main>` | Main body | <main>[Content]</main> |
| `<section>[Content]</section>` | Section | <section>[Content]</section> |
| `<article>[Content]</article>` | Article | <article>[Content]</article> |
| `<footer>[Content]</footer>` | Footer | <footer>[Content]</footer> |

More tags on W3Schools: https://www.w3schools.com/html/default.asp

<a name="css"></a>
# CSS
To-do

<a name="bootstrap"></a>
# Bootstrap
To-do

<a name="git"></a>
# git

## git clone
Clones a repo onto your local machine.
Syntax: git clone (repo link)
Example: 
```
git clone git@github.com:AnthonySLuong/Testing.git
```

## git status
Returns the status of all working files. Will list all untracked files.
Syntax: git status
```
git status
```

## git add
Adds all untracked files to staging area
Syntax: git add (file1) (file2)
Can add one or multiple files.
. add untracked file
```
git add .
```

## git commit
Commit all tracked file in staging area to repo
Syntax: git commit -m “(commit message)”
	Message should be a quick note about the changes made
Example: 
```
git commit -m “First Commit”
```

## git checkout
Checks out a commit(Versions) at any point of time. 
Syntax: git checkout (Branch name)
Example: 
```
git checkout TestBranch
```

## gt pull
Pull any new changes made from remote repo
Syntax: git pull
Example: 
```
git pull
```

## git push
Push any new changes from local repo to remote repo
Syntax: git push
Example: 
```
git push
```

## Workflow
Usually you use the commands in these orders when working on any project
Make sure to always pull before push:
```sh
git status                # Check untracked file
git pull --rebase         # To make sure you are update with the remote repo
git add .                 # add file to staging area
git commit -m "(Message)" # Make the commit
git push                  # Push changes to remote repo
```









