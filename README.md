# Cipher Crawler (Casper Edition)

A small tool for crawling the internal links of a web application and generating a visual map of the site's structure.


## Dependencies

Ensure that [CasperJS](http://casperjs.org/) is installed. On OS X, you can accomplish this with [Homebrew](http://brew.sh/) by running:

```shell
brew install casperjs --devel
```

## Starting the Crawler

To start the crawler, run the following from the project root:

```shell
casperjs start.js --cookies-file=cookies.txt > output.txt
```
