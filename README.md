# Reveal.js Slideshow

This repository contains a `reveal.js` slideshow. `reveal.js` is an open-source HTML presentation framework that enables users to create beautiful and interactive slideshows.

## Running the Slideshow Locally

To run the slideshow locally, you can use the `script/server` command. This will start a local web server, and you can view the slideshow by navigating to the provided URL in your web browser (usually `http://localhost:4000`).

```bash
./script/server
```

## Customizing the Slideshow

### Content

The content of the slideshow is written in Markdown and can be found in the `_posts/` directory. Each Markdown file in this directory represents a slide or a section of a slide. You can edit these files to change the content of your presentation. New slides can be added by creating new Markdown files in this directory, following the naming convention `YYYY-MM-DD-title.md`.

### Appearance

The appearance of the slideshow can be customized by modifying the SASS files in the `_sass/` directory. These files control the styling of the presentation, including colors, fonts, and layout. Key files to look at include:

- `_sass/revealjs/theme/template/settings.scss`: For theme-specific variables like colors and fonts.
- `_sass/revealjs/theme/template/theme.scss`: For the main theme styles.

After making changes to SASS files, you might need to restart the local server or ensure your environment recompiles SASS to CSS for the changes to take effect.
