# code_for_space

This repository contains the content and source code for generating the code_for_space homepage.

This Project is hosted at https://code-for-space.github.io

## Prerequisites

The following are basic prerequisites for previewing the code_for_space homepage on your local machine:

* [Install Hugo](https://gohugo.io/getting-started/installing/) for your specific platform.
If you install from the [release page](https://github.com/gohugoio/hugo/releases), make sure you download the `_extended` version which supports SCSS.

## Cloning the 

The following will clone the project repository onto your local machine.
This will allow you to edit and preview changes to the project site (don't forget to use `--recurse-submodules` or you won't pull down some of the code you need to generate a working site).

```bash
git clone --recurse-submodules --depth 1 https://github.com/code-for-space/code-for-space.github.io.git
cd code-for-space.github.io
```

## Running the website locally

Once you've cloned the project repo, you can run your own local Hugo server:

* Follow the instructions in [Getting started](https://gohugo.io/getting-started/installing/) to install Hugo. You'll need at least *Hugo version 0.68.3*.
  If you install from the [release page](https://github.com/gohugoio/hugo/releases),
  make sure you download the `_extended` version which supports SCSS.
* You will also need to install [Asciidoctor](https://asciidoctor.org/).
* Run `hugo serve` in the site root directory. By default your site will be available at `http://localhost:1313`. Hugo will watch for changes to the content and automatically refresh your site.

```bash
 hugo serve
```
