# Sci-Hub Downloader (Alfred extension)

Alfred Workflow for viewing and downloading scientific papers from Sci-Hub via DOI.

## Setup

1. Set a download path as environmental variable (`path`).
2. Set the Sci-Hub domain which you want to use (default: `https://sci-hub.hkvisa.net`) as environmental variable (`scihuburl`).

# Usage

Enter `doi` followed by `o` to open the paper on Sci-Hub or `d`to download the paper directly.

![](/screenshot1.png)

## Dependencies

**HomeBrew**

Read [this manual](https://brew.sh/index_de) explaining how to install HomeBrew on your Mac. 

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

**wget**

In order to download papers directly you have to [install](https://formulae.brew.sh/formula/wget) `wget`.

```
brew install wget
```


