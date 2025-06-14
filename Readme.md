# Leverless Controller using Kailh PG1316S Switches
![IMG_20250601_125428882](https://github.com/user-attachments/assets/3281f8af-c7a5-4883-963a-b6ac18b1b58f)
![449857277-e4e7f3a8-3f29-4d39-ae58-e3a610ff5cce](https://github.com/user-attachments/assets/b92f124e-4863-4db2-85d0-28cf6eed47ab)


This is a leverless controller using Kailh PG1316S Switches. This design was inspired by the [Mpress Nano](https://paradisearcadeshop.com/collections/mpress-nano/products/mpress-nano-leverless-gaming-controller), the [ULP Dactyl](https://github.com/jonboh/ulp-dactyl), and [u/dynam1keNL](https://www.reddit.com/user/dynam1keNL/)’s work. It’s basically a keyboard that uses a Nice Nano v2 microcontroller.

I prefer to have thumb keys to be angled, hence the thumb module's choice over traditional leverless controllers.

A few notes:

- I placed ~0.4mm thick lens cloth pieces underneath the keycaps. On top of dampening the switch's press it also limits the total key travel to about 1.4mm.
- I avoided using solder wire at the mounting corners of the switches and used the minimum amount of solder paste instead. Using too much solder could create a solder ball that could interfere with the spring leaf operation when bottomed out.
- Currently the design uses a Nice Nano v2 but without bluetooth. However you can edit my design to make the controller wireless relatively easily.
- My original design used the round keycaps from the Mpress Nano, which were designed for Cherry ULP switches but still fit. However, due to their overhang design, pressing the keycap at the edge would make the keycap pop off, so I went with the [keycaps](https://holykeebs.com/products/kailh-pg1316s-keycaps?pr_prod_strat=jac&pr_rec_id=4921d68ec&pr_rec_pid=9503293014306&pr_ref_pid=9401154699554&pr_seq=uniform) from holykeebs.
- Pressing the thumb key with enough force will make the controller slide across the table, so I also designed some wrist rests that can be placed around the controller to limit this.
- The ZMK firmware for the Nice Nano v2 can be obtained and edited from my other repository: [Ultra Low-Profile (ULP) Controller Zmk](https://github.com/Edwards2718/Cherry-ULP-Controller-ZMK-Firmware)

Future Design Improvements

- Improving the thumb module’s support design. I had to choose between a sturdier thumb module and one that would touch my hand during use. I went with the thinner design but with more time I could have made it better.  
