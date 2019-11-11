# DirectTV DECA adapter


binwalk output
```
DECIMAL       HEXADECIMAL     DESCRIPTION
--------------------------------------------------------------------------------
262200        0x40038         RAR archive data, first volume type: MAIN_HEAD
407944        0x63988         RAR archive data, first volume type: MAIN_HEAD
458878        0x7007E         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
458930        0x700B2         HTML document header
460577        0x70721         HTML document footer
460644        0x70764         HTML document header
461267        0x709D3         HTML document footer
461402        0x70A5A         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
461455        0x70A8F         HTML document header
466667        0x71EEB         HTML document footer
466802        0x71F72         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
466855        0x71FA7         HTML document header
474481        0x73D71         HTML document footer
474548        0x73DB4         HTML document header
474714        0x73E5A         HTML document footer
474850        0x73EE2         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
474903        0x73F17         HTML document header
486334        0x76BBE         HTML document footer
486400        0x76C00         GIF image data, version "89a", 145 x 59
489330        0x77772         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
489383        0x777A7         HTML document header
495336        0x78EE8         HTML document footer
495404        0x78F2C         HTML document header
495555        0x78FC3         HTML document footer
495620        0x79004         HTML document header
495938        0x79142         HTML document footer
496074        0x791CA         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
496127        0x791FF         HTML document header
499787        0x7A04B         HTML document footer
499922        0x7A0D2         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
499975        0x7A107         HTML document header
502833        0x7AC31         HTML document footer
502900        0x7AC74         HTML document header
503116        0x7AD4C         HTML document footer
655416        0xA0038         RAR archive data, first volume type: MAIN_HEAD
801160        0xC3988         RAR archive data, first volume type: MAIN_HEAD
852094        0xD007E         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
852146        0xD00B2         HTML document header
853793        0xD0721         HTML document footer
853860        0xD0764         HTML document header
854483        0xD09D3         HTML document footer
854618        0xD0A5A         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
854671        0xD0A8F         HTML document header
859883        0xD1EEB         HTML document footer
860018        0xD1F72         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
860071        0xD1FA7         HTML document header
867697        0xD3D71         HTML document footer
867764        0xD3DB4         HTML document header
867930        0xD3E5A         HTML document footer
868066        0xD3EE2         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
868119        0xD3F17         HTML document header
879550        0xD6BBE         HTML document footer
879616        0xD6C00         GIF image data, version "89a", 145 x 59
882546        0xD7772         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
882599        0xD77A7         HTML document header
888552        0xD8EE8         HTML document footer
888620        0xD8F2C         HTML document header
888771        0xD8FC3         HTML document footer
888836        0xD9004         HTML document header
889154        0xD9142         HTML document footer
889290        0xD91CA         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
889343        0xD91FF         HTML document header
893003        0xDA04B         HTML document footer
893138        0xDA0D2         Unix path: /www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
893191        0xDA107         HTML document header
896049        0xDAC31         HTML document footer
896116        0xDAC74         HTML document header
896332        0xDAD4C         HTML document footer
```

dmesg enumeration
```
usb 1-4.4.3.1.1: new full-speed USB device number 16 using xhci_hcd
usb 1-4.4.3.1.1: New USB device found, idVendor=04b4, idProduct=6285, bcdDevice= 1.17
usb 1-4.4.3.1.1: New USB device strings: Mfr=1, Product=2, SerialNumber=0
usb 1-4.4.3.1.1: Product: Power Control Tools
usb 1-4.4.3.1.1: Manufacturer: WNC MoCA Adatpor
hid-generic 0003:04B4:6285.0007: hiddev3,hidraw6: USB HID v1.11 Device [WNC MoCA Adatpor Power Control Tools] on usb-0000:00:14.0-4.4.3.1.1/input0
```
