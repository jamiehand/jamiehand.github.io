# jamiehand.github.io

- Run locally with: `bundle exec jekyll serve`
- Serves at localhost:4000
- For more help: https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/

## To add an image

- Add image to `/_site/img/photos/original` directory (do NOT create a subdirectory
  here; photos in subdirectories don't seem to get propagated to the
  `large` and `small` directories).
- Run `bundle exec jekyll serve`
  - `/_site/img/photos/large` and `/_site/img/photos/small` should now have
    corresponding images to the ones that you placed in the `original`
    directory.
- Copy the newly updated `/_site/img/photos` directory, and paste it into
  `/img/` directory (replacing the old `/img/photos` directory).
