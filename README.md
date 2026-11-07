# XBPS Templates

Custom XBPS templates for Void Linux.

## Usage

Add repositories to `/etc/xbps.d/00-repository-pi66.conf`:

```sh
echo "repository=https://build.pi66.xyz/repos" > /etc/xbps.d/00-pi66-repository.conf
echo "repository=https://build.pi66.xyz/repos/nonfree" >> /etc/xbps.d/00-pi66-repository.conf
```

Update the package index:

```sh
xbps-install -S
```

## Acknowledgements

- [Void Linux](https://github.com/void-linux/void-packages)
