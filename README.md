# Bollywood Api

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This API allows you to search through a list of bollywood actors and actresses. You can search on:

- Name
- Age
- Gender

# Parameters

Use Capital letters for pronouns and nouns.
Age and gender queries with multiple matches will return ALL matches.

- /name?name=query - returns all names on file Also use POST to add a new Bollywood actor
- age?age=query - age will return all actors and actresses of this age
- /gender/:Male or Female - params
