# monocle-nrf52dk

This repo holds extra firmware that can be added to
[monocle-micropython](https://github.com/brilliantlabsAR/monocle-micropython)
to make it run on the
[nRF52-DK](https://www.nordicsemi.com/Products/Development-hardware/nRF52-DK).

```
cd monocle-micropython
git clone https://github.com/josuah/monocle-nrf52dk
sed -i s/monocle-core/monocle-nrf52dk/g Makefile
cp modules/_mountramfs.py modules/_mountfs.py
make flash
```

* [DONE] Red LED -> LED 1
* [DONE] Green LED -> LED 2
* [DONE] Touch button A -> Physical button 1
* [DONE] Touch button B -> Physical button 2
* [DONE] Touch button interrupt
* [DONE] RAM-based filesystem
* [TODO] Power events -> Physical button 3
