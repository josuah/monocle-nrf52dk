# monocle-nrf52dk

This repo holds extra firmware that can be added to
[monocle-micropython](https://github.com/brilliantlabsAR/monocle-micropython)
to make it run on the
[nRF52-DK](https://www.nordicsemi.com/Products/Development-hardware/nRF52-DK).

```
cd monocle-micropython
git clone https://github.com/josuah/monocle-nrf52dk
sed -i s/monocle-core/monocle-nrf52dk/g Makefile
make flash
```
