# MPYEditor

![image](https://github.com/patfrench/patfrench.github.io/assets/44723412/6d870a2a-7e90-4de3-92d0-81126be5b87e)



MPYEditor is a MicroPython editor that implements the following APIs:
- webUSB
- webBLUETOOTH

<u>To use it, you will need:</u>

![img](https://github.com/patfrench/patfrench.github.io/assets/44723412/77e9bccf-22b5-4787-a4fd-cf188a700c7c)

A [RPi PICO (download firmware)](https://github.com/patfrench/patfrench.github.io/blob/main/firmware%20RP2_PICO/) or [RPi PICO W (download firmware)](https://github.com/patfrench/patfrench.github.io/blob/main/firmware%20RP2_PICO_W/) if you want Bluetooth
With these APIs, your browser will have access to the hardware.

To flash your board, you need to hold down the 'BOOTSEL' button and connect the USB port. A mass storage device will be created, and you will need to copy and paste the firmware.uf2 into it.

Regarding the REPL and indentations, you will need to press ENTER multiple times instead of BACKSPACE (each ENTER will act as a BACKSPACE).
***
***
## Mode WebUSB
You will get this prompt :
``` MPY: soft reboot
FAITMicroPython v1.22.0-preview.5.gd2a9d70c0.dirty on 2023-11-03; Raspberry Pi Pico W with RP2040
Type "help()" for more information.
>>>
```

![usb1](https://github.com/patfrench/patfrench.github.io/assets/44723412/0ffb38cc-9555-44ed-87e4-eaa89a42d00a)
![usb2](https://github.com/patfrench/patfrench.github.io/assets/44723412/43f24231-2dc1-43c4-a038-c5226fee837c)
![usb3](https://github.com/patfrench/patfrench.github.io/assets/44723412/42666fe9-a9a3-4156-bc1d-8d4acce98028)

***
***
## Mode WebBLUETOOTH
You will get this prompt :
```
>>>
```
![ble1](https://github.com/patfrench/patfrench.github.io/assets/44723412/baf5cd9b-99ac-47cf-b84c-99eadaaf3bec)
![ble2](https://github.com/patfrench/patfrench.github.io/assets/44723412/8a761ed5-df8f-4022-a843-b64229e67df8)
![ble3](https://github.com/patfrench/patfrench.github.io/assets/44723412/a91da516-dcb8-4744-a2e9-edbb25464125)

***
***
## Compatibilty
![browser ble](https://github.com/patfrench/patfrench.github.io/assets/44723412/54e9e3be-3285-428a-8eee-eb95678944b8)

![browser usb](https://github.com/patfrench/patfrench.github.io/assets/44723412/6a18f52f-981b-4dd9-9ea4-689f57301426)

***
***
## TODO
- [ ] English comment
- [ ] Add interaction with the PyScript terminal
- [ ] Create new pages in the top right menu
- [ ] Add Bokeh graphs for ADC readings
- [ ] Change PASTE MODE to RAW PASTE



