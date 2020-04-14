# RPS Bootstrap

This project is for you to type along with the Introduction to Bootstrap video. There are no automated tests, so `rails grade` won't do anything.

Experiment!

## Target

Here is the target that we're aiming for in this project:

[https://rps-bootstrap.matchthetarget.com/](https://rps-bootstrap.matchthetarget.com/)

## Snapshot of RPS CSS workspace

The starting point of this project is the ending point of RPS CSS. Here is a snapshot of the workspace I ended up with from the RPS CSS workspace, in case you want to look at it:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#snapshot/9e7bf128-2b92-4eb5-8e0b-2db5dbe129f2)

I slightly re-organized the CSS afterwards; you can see the differences here, in this [git diff](https://github.com/demostudent10-appdev/rps-css/commit/5b527ed0d419c0d7c1a762bd287e36a9948ea4e4).

## Font Awesome

Search for [Font Awesome icons here](fontawesome.com/v5.0.13/icons?d=gallery&m=free).

## Asset links for every HTML doc

I place these in the `<head>` of _almost_ every HTML document I write:

```html
<!-- Expand the number of characters we can use in the document beyond basic ASCII 🎉 -->
<meta charset="utf-8">

<!-- Connect Font Awesome CSS -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css">

<!-- Connect Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">

<!-- Connect Bootstrap JavaScript and its dependencies -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"></script>

<!-- Make it responsive to small screens -->
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
```

## Standard Workflow

 1. Start the web server with `bin/server`.
 1. Navigate to your live application preview.
 1. As you work, remember to navigate to `/git` and **Always Be Committing.**
