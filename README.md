# swisspy.github.io

Repository for the source code of the Swiss Python Conference web site.

## Development

Clone the repository including submodules.

    git clone --recursive https://github.com/SwissPy/SwissPy.github.io

Switch to the `source` branch.

    cd SwissPy.github.io
    git checkout source

Install dependencies.

    pip install -r requirements.txt

Run the devserver.

    make devserver

Now you can browse the website at `http://localhost:8000/`.

## Deployment

For deploying the website, the rendered HTML needs to be pushed to the `master`
branch. This can be done via the `Makefile` and the `ghp-import` script:

    make github

The current version should be live now.
