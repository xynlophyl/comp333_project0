# HTML and CSS Tutorial Exercises for COMP 333

Created by Sebastian Zimmeck for
Wesleyan University - COMP 333: Software Engineering

## Getting Started with GitHub Pages and CSS flexbox

1. Set up a website via GitHub Pages (start by creating a new repo and enabling
GitHub Pages in its settings)
2. Commit and push the HTML and CSS files of this tutorial to your repo
3. Create a new section at the bottom of your website with a CSS flexbox
    - To create a flexbox use `display: flex`. Below is an example to get you
    started. Include it in the sample html and CSS files.
    - Change the flexbox such that it wraps around when a user of your site
    decreases the browser window

    ```css
      /* 
        Include in CSS file.
      */
      .flex-container {
          display: flex;
          flex-wrap: nowrap;
          background-color: orange;
        }

      .flex-container > div {
          background-color: grey;
          width: 200px;
          margin: 10px;
          text-align: center;
          line-height: 75px;
          font-size: 30px;
      }
    ```

    ```html
      <!-- 
        Include in html file.
      -->
      <h1>A CSS flexbox</h1>

      <div class="flex-container" style="width: 100%;">
        <div>This</div>
        <div>Must</div>
        <div>Be</div>  
        <div>The</div>
        <div>Place</div>
        <div>(Naive</div>
        <div>Melody)</div>
      </div>
    ```
