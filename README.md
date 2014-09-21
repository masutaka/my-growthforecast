# My GrowthForecast

## Install

    $ sudo apt-get -y build-dep rrdtool
    $ carton install --deployment

## Boot

    $ carton exec growthforecast.pl --data-dir . --enable-float-number &
