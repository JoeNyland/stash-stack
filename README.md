# stash-stack

Stash stack for Portainer.

## Setup

Start the stack from Portainer, using this repo as the source.

After the container has started and before media is indexed, the directory structure that Stash expects needs to be created:

```bash
# From within the container
cd /config
mkdir -p blobs cache generated/tmp metadata scrapers
```

On _Settings_ > _System_, set _Binary data filesystem path_ to `/var/lib/stash/blobs`.