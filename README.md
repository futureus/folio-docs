# Future Folio Documentation

Customer documentation for using Folio.

## What?

Static HTML served from Github Pages

## Why?

This was migrated from Rackspace (uk39.rs.future.net.uk) to save :money_with_wings:

## How?

Although the repo is private, Github Pages serves content in the `gh-pages` branch publicly at http://futureus.github.io/folio-docs

`gh-pages` has been set as the master branch so beware!

The `CNAME` file then contains the domain name for this Page

`docs.futurefolio.futureplc.com`

You then create a CNAME entry in the DNS zonefile to point at Github Pages.

`docs.futurefolio IN    CNAME   futureus.github.io`
