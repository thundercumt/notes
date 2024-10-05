# List input devices
```
xinput list


⎡ Virtual core pointer                          id=2    [master pointer  (3)]
⎜   ↳ Virtual core XTEST pointer                id=4    [slave  pointer  (2)]
⎜   ↳ 2.4G Mouse                                id=11   [slave  pointer  (2)]
⎜   ↳ 2.4G Mouse Consumer Control               id=12   [slave  pointer  (2)]
⎜   ↳ ELAN07B0:00 04F3:3244 Touchpad            id=14   [slave  pointer  (2)]
⎜   ↳ ELAN07B0:00 04F3:3244 Mouse               id=15   [slave  pointer  (2)]
⎣ Virtual core keyboard                         id=3    [master keyboard (2)]
    ↳ Virtual core XTEST keyboard               id=5    [slave  keyboard (3)]
    ↳ Power Button                              id=6    [slave  keyboard (3)]
    ↳ Video Bus                                 id=7    [slave  keyboard (3)]
    ↳ Power Button                              id=8    [slave  keyboard (3)]
    ↳ Sleep Button                              id=9    [slave  keyboard (3)]
    ↳ 2.4G Mouse                                id=10   [slave  keyboard (3)]
    ↳ 2.4G Mouse System Control                 id=13   [slave  keyboard (3)]
    ↳ Wireless hotkeys                          id=17   [slave  keyboard (3)]
    ↳ HP WMI hotkeys                            id=18   [slave  keyboard (3)]
    ↳ 2.4G Mouse Consumer Control               id=19   [slave  keyboard (3)]
    ↳ AT Translated Set 2 keyboard              id=16   [slave  keyboard (3)]

```

# Enable/disable laptop default keyboard
```
xinput enable "AT Translated Set 2 keyboard"

xinput disable "AT Translated Set 2 keyboard"
```