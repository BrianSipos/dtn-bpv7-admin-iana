# Bundle Protocol Version 7 Administrative Record Types Registry

The internet-draft is hosted at [draft-sipos-dtn-bpv7-admin-iana](https://datatracker.ietf.org/doc/draft-sipos-dtn-bpv7-admin-iana/).

A local build of the current main branch is available [draft-ietf-dtn-bpv7-admin-iana.html](https://briansipos.github.io/dtn-bpv7-admin-iana/draft-ietf-dtn-bpv7-admin-iana.html) with its [misspelling.txt](https://briansipos.github.io/dtn-bpv7-admin-iana/misspelling.txt).

Prerequisites to building can be installed on Ubuntu with:
```
sudo apt-get install -y cmake xml2rfc xmlstarlet aspell python3
```
and then the document can be built with
```
cmake -S . -B build
cmake --build build
```
