# Ruby skeleton project

## Usage

To change the project's `NAME`, execute this in console:

    wget .gitignore https://raw.githubusercontent.com/github/gitignore/master/Ruby.gitignore
    # brew install rename
    find . -exec rename 's/NAME/PROJECT/' {} +

Then initiate the project

    bundle

Remove `.git` folder and the skeleton is ready to work.

## Test

If using unit test:

    rake test

If using rspec

    rake spec

Runinng Guard (with rake-rspec installed already)

    bundle exec guard

