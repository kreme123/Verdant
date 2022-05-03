# Build guide

## Materials
- 20 x [M2x8mm screws](https://www.aliexpress.com/item/32870342767.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl)
- 10 x [M2x14mm standoffs](https://www.aliexpress.com/item/1005001478301407.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl)
- ~50 [1N4148 diodes](https://www.aliexpress.com/item/2025724181.html?spm=a2g0s.9042311.0.0.52114c4d259Ayp)
- 6 x [32mm (OD) x 2.4mm O-rings](https://www.aliexpress.com/item/32908087735.html?spm=a2g0o.order_list.0.0.60cf1802kyAhZY)
- [OLED](https://www.aliexpress.com/item/32896971385.html?spm=a2g0o.order_list.0.0.4c291802RJLFPs)
- [EC11 rotary encoder](https://www.aliexpress.com/item/10000056483250.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl)
- [Encoder knob](https://www.aliexpress.com/item/1005002683252060.html?spm=a2g0o.order_list.0.0.5b901802I6F5Fy)
- [Silicone rubber feet](https://www.aliexpress.com/item/4000439059508.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl)
- [Aluminum feet](https://www.aliexpress.com/item/32947889825.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl)
- [WS2812B led strip](https://www.aliexpress.com/item/32682015405.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl) 60 IP30 (17 leds on one Verdant) 
- [Double sided tape for feet](https://www.aliexpress.com/item/1005001401843627.html?spm=a2g0s.9042311.0.0.52114c4dn6suyl) round 20mm
- [Pro Micro](https://www.aliexpress.com/item/32768308647.html?spm=a2g0o.productlist.0.0.20f5f2022mgoaF)

### Also
- Soldering iron and solder
- Phillips screwdriver
- Flush side cutters
- ~50 MX style switches
- 7u/6.25u and 2u PCB mount stabilizers
- Keycaps (check compatibility)

## Building

Connect Pro Micro to computer and flash "verdant_default.hex" firmware using qmk toolbox

Solder diodes for all keys. Black stripe on diode to square pad on pcb
<a href="https://imgur.com/B3Za0va"><img src="https://i.imgur.com/B3Za0va.jpg" title="source: imgur.com" /></a>

If you want to use encoder, solder jump wires from Pro Micro to PCB
https://golem.hu/guide/pro-micro-upgrade/
<a href="https://imgur.com/1B2dL1g"><img src="https://i.imgur.com/1B2dL1g.jpg" title="source: imgur.com" /></a>

Solder Pro Micro to top side of pcb. Check that pins match. Cut off the excess legs. 
I suggest wearing eye protection and placing something to top of Pro Micro when cutting excess legs. Those legs will fly.
<a href="https://imgur.com/q71w0Xe"><img src="https://i.imgur.com/q71w0Xe.jpg" title="source: imgur.com" /></a>

Add rotary encoder (optional)

Add OLED to top of Pro Micro. Use something like electrical tape between back of oled and top of pro micro to avoid unwanted connection.
<a href="https://imgur.com/kMMEzFK"><img src="https://i.imgur.com/kMMEzFK.jpg" title="source: imgur.com" /></a>

Solder switches and add stabilizers.

Solder rgb strip (optional). Check that strip is correct way (din on strip matches din text on pcb). 
Add soldering iron to rgb strip pins and holes at pcb. Place them closely and heat up to connect them
<a href="https://imgur.com/yCE28Dx"><img src="https://i.imgur.com/yCE28Dx.jpg" title="source: imgur.com" /></a>

Add acrylic cover to pcb using screws and standoffs.

Add O-ring gaskets
<a href="https://imgur.com/FsS0UGJ"><img src="https://i.imgur.com/FsS0UGJ.jpg" title="source: imgur.com" /></a>

## Case

Put screws from the bottom and add standoffs. 

Add legs.

Add case layers 2-4

Add soldered pcb.

Add rest of the case layers 5-7 and screw it in.


