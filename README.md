# CSS Intro Lecture

## Set Up
1. Clone repository
    - click `code` button in github
    - copy url in `code` dropdown
    - in the terminal  (`cd`) to the directory you want to clone the repo
    - `git clone [REPO URL]`
2. Open repo in VSCode
    - navigate (`cd`) into the repo you cloned
    - open the folder with `code [FOLDER NAME]`
    OR 
    - open VSCode > File > Open Folder > Select folder created from clone
3. Create HTML and CSS files
    - click `new file` icon on folder in file explorer
    - create `index.html`
    - click `new file` icon on folder in file explorer
    - create `style.css`

## Code Together
1. Add an h1 tag with the text `CSS Intro Lecture`
2. Add a `div` tag below the header
3. Nest two `p` tags in the div
4. Add lorem ipsum text in the first `p` tag using the VSCode shortcute `lorem`
5. Add lorem ipsum text to the second `p` tag and add a `span` tag between around the first occurrence of the words `ipsum dolor`
6. Link the CSS file in the html head
```HTML
<link rel="stylesheet" href="FILENAME.css">
```
7. Make all paragraphs text blue
    - Add a `p` tag reference in the css 
    - Set the `color` property to blue
8. Make the first paragraph text red
    - Add `first_paragraph` id selector to the first p tag in the HTML
    - Add a `first_paragraph` id reference in the css
    - Set the `color` property to red 
9. Make the background of the page heading and text between span tags yellw
    - Add `yellow_background` class selector to page heading
    - Add `yellow_background` class selector to `span` tag in second `p` tag
    - Add `yellow_background` class reference in the css
    - set the `background-color` property to yellow
10. Push you changes to github
    - Make sure you are in the directory created when you cloned the project
    - Add all changes to be committed `git add -A`
    - Commit all changes with a message `git commit -m "meaningful message"`
    - Push changes to the remote repo `git push`
    - Check that your commit is visible at github.com