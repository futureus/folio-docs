# Future Folio Documentation

## What

Jeykll served static HTML for docs.futurefolio.futureplc.com

This was migrated from Rackspace (uk39.rs.future.net.uk) to save :money_with_wings:

## How

Jekyll will take a copy of the content in htdocs and serve it from the `_site` directory.

## Making changes

###### Local Development

You need at least ruby >=2.0.0. I use rbenv but whatever. You also need the jekyll gem installed.

`gem install jekyll`

###### Branches

`gh-pages` is the branch that live content is served from, so don't push anything there that you don't want to see Live. Use the `develop` branch for that and run Jekyll locally.

###### Going Live

Jeykll will autowatch for new content and build when it has a change to `_config.yml`

* Fork the project
* git clone git@github.com:you/folio-docs.git
* git checkout develop
* *make your changes*
* Run Jeykll locally and test it works
* git add *newfiles.file*
* commit -m "*Commit message here*"
* git push origin develop
* Create a pull request into `gh-pages` branch
* Get Engineering to review and OK it.
