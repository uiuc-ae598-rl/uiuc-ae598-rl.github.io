# AE 598 - MARL

This repository hosts the AE 598 Multi-agent Reinforcement Learning course website.

## Creating the website

The website is built using [Jekyll](https://jekyllrb.com/), hosted on [GitHub](https://github.com/), and served by [GitHub Pages](https://pages.github.com/). The site uses the [Just the Docs](https://just-the-docs.github.io/just-the-docs/) theme and was created using the following steps.

1. Create a repository for the website using the [Just the Docs Template](https://just-the-docs.com/#getting-started). Put the repository in the organization for the course (e.g., "uiuc-ae498-cse") and name it using the [expected GitHub pages repo name](https://pages.github.com/) (e.g., "uiuc-ae498-cse.github.io").

1. Clone the repo.

    ```
    # clone repository locally
    $ cd ../ae498-cse
    $ git clone https://github.com/uiuc-ae498-cse/uiuc-ae498-cse.github.io.git
    ```

1. Install [Jekyll](https://jekyllrb.com/docs/installation/) and Bundler if needed. You might need to make sure the correct ruby version is being used (currently ruby 3). I just used Homebrew for my ruby install, following directions [here](https://mac.install.guide/ruby/13.html).

    ```
    # check if jekyll is installed
    $ jekyll -v

    # check if bundler is installed
    $ bundler -v
    ```

1. Build and preview the site locally to make sure the site works.

    ```
    # change your working directory to the root directory of the site
    $ cd ../ae498-cse/uiuc-ae498-cse.github.io

    # install project dependencies
    $ bundle install

    # build local site
    $ bundle exec jekyll serve
    ```
    Browse to [http://localhost:4000/](http://localhost:4000/).

1. Modify the site as desired. I copied the following files from another course's prior site (e.g., the AE370 2024 Fall [site](https://github.com/uiuc-ae370-2024-fall/uiuc-ae370-2024-fall.github.io)):

    - _config.yml
    - _layouts/
    - _modules/
    - _sass/
    - _staffers/
    - .gitignore
    - assets/
    - docs/
    - environment.yml
    - index.md

1. Build and preview the site again. You might need to exit terminal before doing so.

    ```
    # build local site
    $ bundle exec jekyll serve
    ```
    Browse to [http://localhost:4000/](http://localhost:4000/).

1. Commit and push the changes. The website should automatically update when you push changes on the main branch.

## Updating the website

After creating the initial website, you should be able to just update files as needed. The website should automatically update when you push changes on the main branch.

You can always build and preview the site locally to make sure the changes do what you intend before pushing changes.

    ```
    # change your working directory to the root directory of the site
    $ cd ../ae498-cse/uiuc-ae498-cse.github.io

    # build local site
    $ bundle exec jekyll serve
    ```

  Browse to [http://localhost:4000/](http://localhost:4000/).

## Customization

The schedule was created using files from the [Just the Class](https://kevinl.info/just-the-class/) theme. Specifically, the `/_sass/`, `/_layouts/`, `/staffers/`, and `/_modules/` files were based on corresponding [files](https://github.com/kevinlin1/just-the-class) from that theme.

## Contact

Feel free to contact Huy Tran (huytran1@illinois.edu) with any questions!
