# hugo-github-pages-poc

## Prerequisites

    # install homebrew
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    # install prereqs
    brew install git hugo


## Adding new pages
    
    cd docs

    hugo new blog/my-first-post.md

    hugo new page/my-first-page.md
    
    git status


## Start the dev server

    cd docs
    hugo server -D

    # in another shell
    open http://localhost:1313/hugo-github-pages-poc/

    open https://clarson99.github.io/hugo-github-pages-poc/

