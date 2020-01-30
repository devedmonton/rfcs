## Welcome To The Dev Edmonton Society RFC Repository

This is an **EXPERIMENTAL** repository where we're prototyping an RFC process that we can use to be more open and collaborative with our members and community in the future.

Contact @Mark on Slack, or @MarkBennett on GitHub for details.

### Building The RFC site locally

This prototype uses Jeykll with Github Pages plugins, so that content can be quickly published and served as a Github Page. To build locally you'll need to install Ruby 2.1+.

With Ruby 2.1+ installed, you'll want to install dependencies using bundler.

    bundle install

From this point you can build and serve the site using:

    bundle exec jekyll serve -H 0.0.0.0 -p 4000

This will serve the site at:

    http://localhost:4000

Changes will be detected and the site regenerated automatically. If you change the Jekyll configuration then you'll need to stop the server and start it again.