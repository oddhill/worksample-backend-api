# PHP API Work Sample

This repository contains everything you will need to create your work sample
when applying as a backend developer at Odd Hill with a focus on PHP and APIs.

## The API

The API you will be building will be exposing data about books the authors
of these books and the genres of the books.

### It should be possible to get data from the API in the following ways

- List all books
- List all authors
- List all genres
- List all authors for a specific book
- List all books for a specific author
- List all genres for a specific book
- Get a single book by ID
- Get a single author by ID
- Get a single genre by ID

## Expectations

We expect you to build an API in your PHP framework of choice. You are free to
use an API specification you feel comfortable working with but an API built on
a REST specification or GraphQL is preferred.

The finished work sample should have a readme describing how to get the API up
and running.

We expect you to host the code as a repository on Github or GitLab under your
own profile.

## Data source

In this repository you will find database dumps for the data required to build
the API. There are database dumps available for MySQL and SQLite.

## If you have the time

The following items are not required but if you have the time feel free to
implement them. Do note though that we will review these extras in the same way
we review the base work sample.

### Additional ways to get data

- Search for books by ISBN
- Search for books by title
- Search for authors by name
- Search for genres by name

### Integrate with external APIs

Integrate with external APIs to fetch additional data like the cover image,
reviews and more. Good APIs to integrate with could be one of the following.

#### Google Books

https://developers.google.com/books/

#### Open Library

https://openlibrary.org/developers/api

## If you have even more time

Build a basic administrative interface protected by authentication where
admins can manage the library of books.

The administrative interface would preferably be built with PHP and a
templating language of choice.

You will not be required to wite your own css. A frontend framework like
Boostrap is perfectly acceptable.

### As a administrator you should be able to do the following

- Create, edit and delete books.
- Create, edit and delete authors.
- Create, edit and delete genres.

## Remember to have fun!

This work sample is not about pointing fingers if something is off. We want to
see how you think and how you adapt requirements into code.
