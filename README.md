# legal.palaceproject.io

This repo is a simple github pages site that contains the legal documents used for the Palace Project.

- EULA [[Published](https://legal.palaceproject.io/End%20User%20License%20Agreement.html)] [[Markdown](docs/End%20User%20License%20Agreement.md)]
- Privacy Policy [[Published](https://legal.palaceproject.io/Privacy%20Policy.html)] [[Markdown](docs/Privacy%20Policy.md)]

## Original Files

The original word files from our lawyer are stored in the [word](/word) folder and markdown versions are stored
in the [docs](/docs) folder and published to https://legal.palaceproject.io with github pages.

### Conversion

The word documents were converted to github markdown using [pandoc](https://pandoc.org/) with the `gfm` output type. The generated markdown was then touched up by hand in order to get them to look correct in github pages.

## Local editing

You can edit the pages locally and see what the changes will look like by running the following commands from the root of this github repo: 
```
cd docs
bundle install
bundle exec jekyll serve --incremental
```
