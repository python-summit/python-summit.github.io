# swisspy.github.io

Repository for the source code of the Swiss Python Conference web site.

## Development

Clone the repository.

    git clone https://github.com/SwissPy/SwissPy.github.io

Switch to the `source` branch.

    cd SwissPy.github.io
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

    pipenv run make clean html
    pipenv run make github

The current version should be live now.
