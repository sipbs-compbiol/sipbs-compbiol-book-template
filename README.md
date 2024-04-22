# README.md sipbs-compbiol-book-template

This repository is a template, intended as a convenience to take some manual work out of setting the style for Quarto books used by SIPBS Computational Biology.

This version of the template includes:

- a GitHub Action (`.github/workflows/publish.yml`) that should update the GitHub Pages version of the book on each push to the `main` branch.
- an example WebR page

## How to use this template

### Setting Up

1. Click on the `Use This Template` button to create a new repository/project based on this template
2. Clone or download the project to your local development environment
3. Open the project folder and modify `_variables.yml` to change:
  - `[A]` academic year
  - `[B]` administrator name and contact information
  - `[C]` GitHub URLs for the repository
4. Modify `_quarto.yml` to change:
  - `[A]` book title
  - `[B]` footer text
  - `[C]` GitHub repository URL
  - `[D]` author name and publication/presentation date
  - `[E]` chapters and sections
5. Modify `DESCRIPTION` to change:
  - `[A]` package name and book title
  - `[B]` author names and emails
  - `[C]` repository URL
  - `[D]` required R packages
  - `[E]` licensing information
6. Change or update the licence, if required
7. Add the `quarto-webr` extension (if necessary) using the command `quarto add coatless/quarto-webr`
8. Generate the book by issuing `quarto render` in the terminal, or using the `Render` button in `RStudio`
9. Commit your updates in the local development environment
10. Publish your book to GitHub Pages by issuing `quarto publish gh-pages` in the terminal

### General Usage

1. Make changes to the `.qmd` files, updating chapter information in `_quarto.yml`, as needed for your material
2. Commit your changes locally to the git repository
3. Push your changes to the GitHub repository