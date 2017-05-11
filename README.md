[![Coverage Status](https://coveralls.io/repos/github/Jchinonso/inverted-index-api/badge.svg?branch=server-side)](https://coveralls.io/github/Jchinonso/inverted-index-api?branch=server-side)
[![Build Status](https://travis-ci.org/Jchinonso/inverted-index-api.svg?branch=master)](https://travis-ci.org/Jchinonso/inverted-index-api)


# Inverted Index
Elasticsearch uses a structure called an inverted index, which is designed to allow very fast full-text searches.
An inverted index consists of a list of all the unique words that appear in any document, and for each word, a list of the documents in which it appears.

## Installation
- Clone this repository to have this app on your machine 
- Then run ```npm install```  to install the dependencies
- Start the server with gulp by running ```gulp serve```

## Usage
Make sure you have created some valid JSON files on your machine to test the API with.
A valid JSON file must have .json extension and must have the following structure:
```[
  {
      “title”: “An inquiry into the wealth of nations”,
      “text”: “This string seeks to help you understand the problem set”
  },
  {
      “title”: “From third world to first world”,
      “text”: “This string is also to help you understand the problem set”
  }
]
```
