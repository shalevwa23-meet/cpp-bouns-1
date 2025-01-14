Explanation in "cpp bonus1.pdf".

All required instalations are included in the colab notebook (run them please)

The instalation steps are:

    !git clone https://github.com/podofo/podofo.git

    %cd podofo

    !sudo apt-get install -y libfontconfig1-dev libfreetype-dev libxml2-dev libssl-dev libjpeg-dev libpng-dev libtiff-dev libidn11-dev

    %mkdir build

    %cd build

    !cmake .. -DCMAKE_INSTALL_PREFIX=/usr/local

  !make -j$(nproc)

  !make install

  !ldconfig
