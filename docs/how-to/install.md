# HOW TO INSTALL

We will install directly from the Gitlab repository a small bash script that will
wrap the docker command to start the container for the awesome Fuzzy Finder.

The first time we start the container Docker will pull it from the Docker Hub
if not already present locally.

Please feel free to inspect first the content of the script [here](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/raw/latest/bin/fuzzy-finder).

## From a Terminal

From inside a `bin` folder in your path just run:

```bash
curl -O https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/raw/latest/bin/fuzzy-finder && chmod 700 fuzzy-finder
```

Depending on the operating system you may need to run the above command with
`sudo` before each instruction.


## Testing Installation

```bash
fuzzy-finder --version
```

We should see the version number printed out, otherwise something went wrong.


---

[<< previous](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/docs/the-package/why_exists.md) | [next >>](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/docs/how-to/use.md)

[HOME](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/README.md)
