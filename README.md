# Markdown for IETF Authors

This is the working area for the individual Internet-Draft, "Markdown for IETF
Authors".

* [Editor's
  Copy](https://larseggert.github.io/md-for-authors/#go.draft-vew-md-for-authors.html)
* [Individual
  Draft](https://datatracker.ietf.org/doc/html/draft-vew-md-for-authors)
* [Compare Editor's Copy to Individual
  Draft](https://larseggert.github.io/md-for-authors/#go.draft-vew-md-for-authors.diff)

## Building the Draft

The easiest way to build formatted text and HTML versions of this draft is to
use the [Docker i-d-toolchain](https://github.com/larseggert/i-d-toolchain).

``` shell
docker run \
       --pull always \
       -v $(pwd):/id:delegated \
       --cap-add=SYS_ADMIN \
       ghcr.io/larseggert/i-d-toolchain:latest \
       kdrfc -h -3 draft-vew-md-for-authors.md
```
Alternatively, formatted text and HTML versions of the draft can be built using
`make`. This requires that you have the necessary software installed.  See [the
instructions](https://github.com/martinthomson/i-d-template/blob/main/doc/SETUP.md).

## Contributing

See the [guidelines for
contributions](https://github.com/larseggert/md-for-authors/blob/main/CONTRIBUTING.md).
