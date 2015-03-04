gr-hpsdr
========

gnuradio 3.7 module for HPSDR Hermes / Metis.

Compatible with version 3.7 of gnuradio and versions of Hermes firmware 1.8 through at least 3.1. It will not be compatible with the new HPSDR protocol under development that could be released for Hermes perhaps sometime in 2015.

The alex branch adds fields to control Alexaries (Alex) LPF and HPF filters, transmit and receive antenna selection, and 6m LNA. It has not yet been tested.

To build:
---------

    mkdir build 
    cd build 
    cmake ../ 
    make 
    sudo make install 
    sudo ldconfig 


