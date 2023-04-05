# newhambook
A web-book for future or new hams.

View the web-book at <https://k3cr.github.io/newhambook>.

## Render the book

- Install R.
- Install RStudio.
- Install `renv` via `install.packages('renv')`.
- Connect GitHub to RStudio.
- Copy the repo and create a new RStudio project.
- Install package dependencies via `renv::restore()`.
- Render the book via `bookdown::render_book('src')`.
- View the book in your browser by opening `docs/index.html`.