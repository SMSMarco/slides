<!-- .slide: data-state="title" -->

### Docker




### Agenda

A markdown first presentation framework. Based on reveal.js with preinstalled plugins, a dash of Bootstrap and sweet extras.

<a class="btn btn-lg btn-danger text-white mr-3" href="https://github.com/planetoftheweb/rayveal">Github Repo</a>

### Features


### Marco


### 100% Markdown

- Assumes you use markdown to create slides. The `index.html` file points to a markdown file in `build/slides/demo.md`.
- It does whatever [reveal.js](https://github.com/hakimel/reveal.js) can.


### Persistent Navigation

<small>The persistent navigation bar at the bottom is on every page. It will disappear after 5 seconds. You can also toggle it by hitting the `t` key. Look for the following code on `index.html`</small>

```html
<footer class="footer">
  <div class="persistent">
    <strong>Slides:</strong>
    <a href="https://bit.ly/thenext50">bit.ly/thenext50</a> &bull;
    <strong>Contact:</strong>
    <a href="https://www.linkedin.com/in/planetoftheweb">LinkedIn</a> |
    <a href="https://www.linkedin.com/learning/instructors/ray-villalobos">courses</a>
    | <a href="https://twitter.com/planetoftheweb">@planetoftheweb</a> |
    <a href="https://github.com/planetoftheweb">github</a>
  </div>
  <div class="smaller">Use arrows to navigate, esc for overview</div>
</footer>
```



### Multiple slides

You can use multiple markdown files within the same project, just add a file in the `build/slides` folder.

<small>Press the `m` key to show [sidebar menu](https://github.com/denehyg/reveal.js-menu). You can use it to jump to different slideshows. This list is created using the gulp build process, which generates an `index.json` file for you as you add more markdown files to the `docs/slides` folder.</small>


### Author Notes

You can't see them, but they're there. Speaker notes lets you create notes that only you see. Press the `s`. I also use them so that I know what I'm going to say when using simpler bullets.

> > Author Notes: Author notes are similar to markdown blockquotes, but you use double greater than signs. They won't appear on your slides, so I personally use them as reading notes, but Reveal.js has a presentation mode that allows you to see them in your slides.


# Fragments

1. Are on by default
1. You can write HTML lists<br><small>(If you don't want them)</small>
