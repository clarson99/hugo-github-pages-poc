# hugo-github-pages-poc

## Prerequisites

    # install homebrew
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    # install prereqs
    brew install git hugo


## Adding new pages
    
    cd docs

    hugo new posts/my-first-post.md

    #hugo new -k chapter my/_index.md 
    #hugo new -k chapter my/new/_index.md 
    #hugo new -k default my/new/page.md
    
    git status


## Start the dev server

    cd docs
    hugo server -D

    # in another shell
    open http://localhost:1313/
