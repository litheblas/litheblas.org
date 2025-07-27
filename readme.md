# LiTHe Blås (litheblas.org)
The external site for the student orchestra LiTHe Blås. The site is built with Jekyl and Bootstrap. Keep it simple.

![Screenshot](screenshot.jpg)

## Deploy
The site is hosted on GitHub Pages. To make updates you just need to update the correct page/markdown page and push it to the master branch. The site should be rebuilt and deployed in a couple of moments.

## Development
1. Install [rbenv](https://github.com/rbenv/rbenv?tab=readme-ov-file#installation) and plugin [ruby-build](https://github.com/rbenv/ruby-build?tab=readme-ov-file#installation).
2. Make sure the [build environment](https://github.com/rbenv/ruby-build/wiki#suggested-build-environment) is correct.
3. Install the correct Ruby version with `rbenv install 3.3.4` and set the version by running `rbenv local 3.3.4`
4. Clone down the project locally.
5. Run `bundle install`.
6. Run `bundle exec jekyll serve`.
