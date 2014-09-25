# My GrowthForecast

## Install

    $ sudo apt-get -y build-dep rrdtool
    $ carton install --deployment

## Boot

    $ carton exec -- perl growthforecast.pl --data-dir . --enable-float-number &
