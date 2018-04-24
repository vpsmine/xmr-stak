# XMR-Stak - For Low End VPS (Included OpenVZ)

### Recommended OS:Debian
```
    sudo apt install libmicrohttpd-dev libssl-dev cmake build-essential libhwloc-dev
    mkdir xmr-stak/build
    cd xmr-stak/build
    cmake -DCMAKE_LINK_STATIC=ON -DOpenCL_ENABLE=OFF -DCUDA_ENABLE=OFF -DMICROHTTPD_ENABLE=OFF -DOpenSSL_ENABLE=OFF -DHWLOC_ENABLE=OFF ..
    make install
```
Remember to modify the configuration file.

If you can't finish compiling, prove your VPS is very low-end, but you can use our binary file.
