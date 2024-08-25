# Interactive CYOA GitHub Template
A template to easily host Interactive CYOAs on GitHub.

Features:

* Hyperlinks enabled
* IntCyoaEnhancer's Download Progress Indicator included
* Optional CSS code in the `index.html` to:
    * Make your backgrounds static
    * Change the colour of your Point Bar icons
    * Override the background image in the `project.json`
* Dynamic Background support
   * To learn more, see [here][dynbg]
* Automatic GitHub workflow to republish your site on any change

View the text instructions [below](#instructions) or
[watch the video tutorial](https://www.youtube.com/watch?v=LCvOVB8wZQE).

## Instructions

### Sign up

1. First, [create an account](https://github.com/signup) on GitHub

### Create the repository

1. Press the bright green **Use this template** button at the top of this repo
2. Press **Create a new repository**
3. Give your repository a name, this will be the folder that will be used to
   access your CYOA
4. Press **Create repository**

### Enable GitHub Pages

1. Go into **Settings** → **Pages** and where it says **Build and deployment**
   look for the **Source** dropdown menu. Select **GitHub Actions**

### Uploading your files

1. Press the **Add file** dropdown → **Upload files**
2. Upload your `project.json` (and `images/` if appropriate)

---

That should be all! After a short time (usually ~12s) it should now
automatically begin hosting at `https://YOURUSERNAME.github.io/REPONAME`.

Feel free to remove this file and `LICENSE` to clean up the code even more.

### Video tutorial
Press the thumbnail below to open the video. You may need to open in a new tab
so as to not replace this window.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=LCvOVB8wZQE" target="_blank">
 <img src="http://img.youtube.com/vi/LCvOVB8wZQE/maxresdefault.jpg" alt="Watch the video" width="720" height="405" border="10" />
</a>

## More stuff

### Add the URL to the repository for ease of access
1. Press the settings gear to the right of the **About** section title and
   below the **Star** button.
2. Tick **Use your GitHub Pages website**

Your URL should now display!

### Manually republish without pushing
If you want to republish without adding or modifying files, simply go into the
**Actions** tab → select **Deploy static content to Pages** on the left side →
**Run workflow** → and **Run workflow** again.

### Other styles
To do the CSS stuff mentioned in the Features above, edit your `index.html` and
find the `<style>` section. There will be comments that describe each style.

### Manually do this
If you want to manually do this, check out the **GitHub** section of the ICCT:
[https://icctutorial.pages.dev/publishing/github/][icct-gh]

[icct-gh]: https://icctutorial.pages.dev/publishing/github/

## Acknowledgements

* Thanks to `u/LOLLOL12344` for the simpler CSS code regarding Point Bar icon
  colouring
* Thanks to `3deas_27816` on Discord for the background image code

<!-- URLs -->
[dynbg]: https://icctutorial.pages.dev/appendix/reference/#make-the-background-different-for-each-row

<!-- BUFFER -->