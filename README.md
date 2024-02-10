# Heisig Helper

A simple web page built with Rails that parses a given Japanese sentence and breaks down each kanji into their radical components as they appear in James Heisig's Remembering the Kanji vol. I. The results can be copied into the clipboard.

I created this to supplement my sentence mining process. I was already grabbing word definitions, but occasionally I also wanted to grab the keyword and radicals of unfamiliar kanji.

## Setup

Install Rails 7.1.2 and Ruby 3.2.2.

The sample database in ./storage contains the first 2042 kanji imported from `heisig.csv`. You can initialize your own sqlite3 database with the schema in `/db/schema.rb`, and use `importHeisigCsv.rb` to import the rows from the .csv file.

## Usage

Simply paste a Japanese sentence with kanji to get some results.

