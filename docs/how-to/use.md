# HOW TO USE

This project is simply the Fuzzy Finder we can find [here](https://github.com/junegunn/fzf)
running from a Docker Container, thus in the README of the project we can found
lots of information about the possibilities offered by it.


## Fuzzy Finder Shell

Each time we run the Fuzzy Finder it will drop us in their shell.

```bash
fuzzy-finder
```

will drop us in this shell prompt...

![Fuzzy Finder Shell](https://static.exadra37.com/img/docs/exadra37-docker/cli-tool/fuzzy-finder/fuzzy-finder-shell.png)

From this shell we can filter the files we want to see and preview them in right
side pane.

We can see more details about the search syntax on the [project page](https://github.com/junegunn/fzf#search-syntax).


## Bash Script Options

The bash script that wraps the start of the Docker Container as an option that
let us to specify the host dir where we want to run the Fuzzy Finder.

#### From current directory

To index all files in current directory...

```bash
fuzzy-finder
```

#### From a specific directory

To index all files in a specific directory...

```bash
fuzzy-finder --host-dir /path/to/dir
```
or

```bash
fuzzy-finder --hd /path/to/dir
```

#### Run a specific version

For a specific Fuzzy Finder version...

```bash
fuzzy-finder --tag 0.17.3
```

For the latest stable docker tag...

```bash
fuzzy-finder --tag latest
```

For the latest development docker tag...

```bash
fuzzy-finder --tag dev-latest
```

---

[<< previous](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/docs/how-to/install.md) | [next >>](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/CONTRIBUTING.md)

[HOME](https://gitlab.com/exadra37-docker/cli-tool/fuzzy-finder/blob/master/README.md)
