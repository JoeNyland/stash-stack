# stash-stack

Stash stack for Portainer.

## Setup

Start the stack from Portainer, using this repo as the source.

After the container has started and before media is indexed, the directory structure that Stash expects needs to be created in the volume:

```bash
mkdir -p blobs cache generated/tmp metadata scrapers
```
