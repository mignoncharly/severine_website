# Severine's Data Portfolio

R Markdown portfolio containing data-analysis projects, visualizations, and an embedded Shiny application.

## Repository structure

Source pages are written as .Rmd files; _site.yml defines the generated site and docs/ contains publishable output.

## Local development

Open severine_website.Rproj in RStudio, install the packages referenced by the notebooks, and render the site with rmarkdown::render_site(). Review generated output under docs/ before publishing.

## Repository hygiene

- Do not commit credentials, local environment files, virtual environments, generated caches, or build output.
- Keep project documentation factual and update it alongside behavioral or deployment changes.
- Preserve database and project-data files unless their removal has been reviewed separately.
