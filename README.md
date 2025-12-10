# Brother-printer-Endeavour
How to install a wireless brother printer on Endeavour OS

Install cups
```
pacman -S cups
```

Open the cups gui using [http://localhost:631](http://localhost:631)

In the GUIs, administation panel, add a new printer, give it a resonable name and select a protocol that is supported. I used `ipp` and wrote down in the printers addres
```
ipp://192.168.1.2/ipp/print
```

When asked for a driver, select `ipp everywhere`

