# latex-travis-ci
Test Repo to set up Travis CI with LaTeX

# How to compile with Travis
Simply push a commit with a tag. This creates a release at github and then travis automatically compiles the PDF(s) and publishes them with the release.

For example:

    git add -A
    git commit -m "My commit message"
    git tag "test-1"
    git push --follow-tags

The finished released and build can then be found at `https://github.com/iuf/latex-travis-ci/releases/tag/test-1`


Please tag your build with the date and time. For example: `git tag "build-2015.09.05-18.24`


