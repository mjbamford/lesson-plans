# Lesson Plan
## Topic
## Outcomes

## Materials
1. https://github.com/Ruegen/lesson-plans/blob/master/week-03/day-02.md
1. https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
1. [Grumpy Cat skeletal HTML](./grumpy-cat.html)
1. https://github.com/joshbuchea/HEAD
1. https://validator.w3.org/
## Procedures
Follow the content in [Materials (1)]( https://github.com/Ruegen/lesson-plans/blob/master/week-03/day-02.md)
### Direct Instruction
Describe the structure of [Materials (3)](./grumpy-cat.html)

Tag|Description
---|-----------
`<!DOCTYPE html>`|describes the html favour (HTML5 in this case). Doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML. It's now mostly obsolete.
`<html>`|to wrap everything
`<head>`|for non-content instructions. E.g. keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, etc.
`<body>`|for the content body to display - text, images, videos, audio.
`<meta charset="utf-8">`|to set the character set to UTF-8.
`<title>`|to set the title of your page displayed in the browser tab, bookmarks and SEO. 

Run the world's smallest web server (explain the command line options)
  ```
  ruby -run -e httpd . -p 8000
  ```
Describe typical directory structures for websites: index.html, images, styles, scripts, js, assets

Validate the page using [Materials (4)](https://validator.w3.org/)

### Guided Practice
1. Look up the MDN documentation for `<img>`. What attributes does it take?

### Independant Practice
1. Add a heading to the page.
