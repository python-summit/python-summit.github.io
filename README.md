# Swiss Python Summit Website

Repository for the source code of the Swiss Python website.

## Development

Clone the repository.

    git clone https://github.com/python-summit/python-summit.github.io

Switch to the `source` branch.

    cd python-summit.github.io
    git checkout source

Install dependencies.

    pipenv install

Run the devserver.

    pipenv run make devserver

Now you can browse the website at `http://localhost:8000/`. To stop the server,
run `pipenv run make stopserver`.

## Deployment

For deploying the website, the rendered HTML needs to be pushed to the `master`
branch. This can be done via the `Makefile` and the `ghp-import` script:

    pipenv run make clean github

The current version should be live now.
