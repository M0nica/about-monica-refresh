[![Netlify Status](https://api.netlify.com/api/v1/badges/aa82321f-f79a-4e29-904d-0de984614b16/deploy-status)](https://app.netlify.com/sites/goofy-lewin-3610ce/deploys)

# About Monica Redesigned

<img src="https://raw.githubusercontent.com/M0nica/about-monica-refresh/master/src/assets/img/about-monica-website-screenshot.png" alt="draft of site as of 11-01-17">

## Purpose
This repository houses Monica Powell's web development and design portfolio. It is built using HTML/CSS and JavaScript and was developed from  [Zurb's Foundation for Sites](http://foundation.zurb.com/sites).

It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression
  
## Live Website
<a href="http://wwww.aboutmonica.com">www.aboutmonica.com</a>.



Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
