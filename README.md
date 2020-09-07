# tinyproxy.github.io

this [website](https://tinyproxy.github.io) is generated from the [tinyproxy repo](://github.com/tinyproxy/tinyproxy):

    git clone git://github.com/tinyproxy/tinyproxy
    cd tinyproxy
    autoreconf -i
    ./configure
    make
    cd docs/web
    make

for modifications, do so first in tinyproxy repo, then file PRs with the modified input data over there, then another PR with the generated output data here.

