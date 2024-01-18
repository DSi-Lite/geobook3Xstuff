# not done just yet mb

<a href="https://geo-computers.com/geobook-3x-13-3-laptop-hd-intel-pentium/">geobook 3X webpage on geo-computers.com</a> 

<img src="pcbImages/20240117_220708.jpg" width=20%  height=36% style="transform: rotate(90deg);"></img>
<br>
this is just a pic of the top side (facing keyboard) of the mainboard. specific components are highlighted in red
mainboard has a profile of ~72.90mm by ~155mm

power is recieved through a 3.5mm  dc plug at 12v ~2-3A(?), a suitable replacement being <a href="https://www.lcsc.com/product-detail/AC-span-style-background-color-ff0-DC-span-Power-Connectors_HDGC-DC400170-0961-3H_C7428737.html">the DC400170-0961-3H
</a> plug.

ic/chip | highlighted color | datasheet link | extra notes
---|---|---|---
ITE IT8987E | Red | <a href="http://www.datasheetmeta.com/pdf.php?q=IT8987E">datasheetmeta.com</a> | data sheet might be inaccurate
2x ELPIDA 2GB LPDDR4(?) FA164A2PF-JD-F | Yellow |  | not done yet, datasheet is hard to find, and the chip seems to be EoL
Intel Pentium N4200 | Green | <a href="https://ark.intel.com/content/www/us/en/ark/products/95592/intel-pentium-processor-n4200-2m-cache-up-to-2-5-ghz.html">intel.com</a>
FORESEE NCEMASLD-32G 32GB eMMC | Light Blue | <a href="https://datasheet.lcsc.com/lcsc/2008141506_FORESEE-NCEMASLD-32G_C520992.pdf">lcsc.com</a> | geobook site also specifies a 64gb version
REALTEK ALC269 | Purple | <a href="https://pdf1.alldatasheet.com/datasheet-pdf/download/1132736/REALTEK/ALC269.html">alldatasheet.com</a> | 
[//]: # (https://archive.org/details/REALTEK-alc-269 << archive.org mirror)
the IT8987E handles a good chunk of the I/O probably but doesnt handle usb-c i think
<br> theres alot of unpopulated usb c headers that suggest a possible usb-c interface but i cant find a controller that matches it though lol