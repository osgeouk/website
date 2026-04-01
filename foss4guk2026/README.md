# FOSS4G:UK 2026 Website

This folder is used to host the foss4g:uk 2026 website. The website is located at: [uk.osgeo.org/foss4guk2026/](https://uk.osgeo.org/foss4guk2026/)
Theme used: [DigitaleGesellschaft/jekyll-theme-conference@v3.6.6](https://github.com/DigitaleGesellschaft/jekyll-theme-conference)

## Get started

Install [jekyll](https://jekyllrb.com/docs/installation/)
Run the following

```sh
bundle install 
bundle exec jekyll serve  
```

### Changing Components

Copy from the source plugin theme in the same folder and add onto the code. Don't delete the original code as it might lead to broken behaviour.
For e.g. to change `footer`, follow the steps

- Copy the `footer.html` from source [_includes/partials/footer.html](https://github.com/DigitaleGesellschaft/jekyll-theme-conference/blob/main/_includes/partials/footer.html)
- Create the same folder structure: `touch _includes/partials/footer.html`
- Paste the contents from the source and override/add the code

Further Documentation can be found at: [https://github.com/DigitaleGesellschaft/jekyll-theme-conference/tree/main](https://github.com/DigitaleGesellschaft/jekyll-theme-conference/tree/main)
