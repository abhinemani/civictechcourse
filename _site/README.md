# Civic Technology: Masters Class

Website for the University of Chicago Civic Technology course as part of the CAPP program. 

Site built using the Immaculate theme for Jekyll.

## Immaculate

A beautiful, fast, AMP-compliant Jekyll theme based on Tufte CSS.

[Check it out here!](https://cdn.ampproject.org/c/siawyoung.com/immaculate/)

[Google AMP](https://www.ampproject.org/)

[Tufte CSS](https://github.com/edwardtufte/tufte-css)

Immaculate is really fast, thanks to Google AMP. When served over Google's CDN, you will see typical `DOMContentLoaded` times of well under 100ms (when using the leaner stylesheet, see below). The benefits are most obvious for slower connections. On the *Regular - 2G* throttling setting in Chrome, the demo page still manages a `DOMContentLoaded` of under 500ms.

Immaculate includes tag support for some of the more commonly-used Tufte CSS layout options, including sidenotes, margin notes, and full-width figures. Other features, such as `newthought` or epigraphs, can be used by typing raw HTML in your Markdown files. I might add helper tags for these in the future.

**Caveat (need hep!)**: AMP HTML does not allow form elements, including checkboxes, which are used in Tufte CSS to toggle the display of sidenotes and margin notes at smaller widths. As such, I've modified Immaculate to disable this functionality at smaller widths for the time being. It's a big deal, and I'm looking for help on emulating this functionality without using checkboxes.

### Getting Started

```
git clone git@github.com:siawyoung/immaculate.git
cd immaculate
bundle install
bundle exec jekyll serve --baseurl ''
```

Modify the template files and `_config.yml` to your liking, and publish away!


### Credits

Credits to [Amplify](https://github.com/ageitgey/amplify) for most of the AMP-related code.

## License

MIT