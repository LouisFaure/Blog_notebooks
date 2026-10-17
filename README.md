# Blog_notebooks

Jupyter notebooks behind the blog posts of [louis.faure.dev](https://louis.faure.dev/post/).

The notebooks listed in `posts.toml` are published: the website ([HomePage](https://github.com/LouisFaure/HomePage),
where this repo is the `notebooks/` submodule) converts them to posts in CI, using their saved outputs. To publish a
notebook, run it, save it with its outputs, and add a `[[post]]` entry to `posts.toml`. Start the notebook with a
`# Title` heading; the "Jupyter" badge linking back to the notebook is added by the website build (see `posts.toml`).
