# Mods for Segone "show them your world" 

## About

These instructions show how you can modify Segone tiles to reflect your personal preferences.

Please support Simon's awesome
<a href="https://www.kickstarter.com/projects/segonefantasystl/segone-show-them-your-world-stl-and-pdf-fantasy-map" target="_blank">Segone: show them your world (stl and pdf fantasy map)</a> campaign 
on 
<a href="https://www.kickstarter.com/projects/segonefantasystl/segone-show-them-your-world-stl-and-pdf-fantasy-map" target="_blank">Kickstarter</a>!

## Replace original "H" connectors by OpenLOCK clipping

![OpenLOCK Sample 1](./img/openlock-sample01.jpg)

### 0. Prerequisites

- Install latest version of [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/)

### 1. Load Segone tile

![OpenLOCK Step 1](./img/openlock-step01.png)

### 2. Add solid mod part

   > Note: This is to remove the original "H" holes

Right-click the model and select "Add part" > "Load ..." 

![OpenLOCK Step 2](./img/openlock-step02.png)

Select the file [`openlock/segone_solid-base.stl`](./openlock/segone_solid-base.stl)
   
### 3. Align the solid mod part

- Overwrite the position of the just added part by setting both it's x- and y-position to 0
- Align z-position to the ground by clicking the "Drop to bed" icon

![OpenLOCK Step 3](./img/openlock-step03.png)

It should now look like this:

![OpenLOCK Step 4](./img/openlock-step04.png)

### 4. Add negative mod part

   > Note: This is to cut out the OpenLOCK holes

Right-click the model and select "Add negative volume" > "Load ..." 
   
![OpenLOCK Step 5](./img/openlock-step05.png)
   
Select the file [`openlock/segone_openlock-negative.stl`](./openlock/segone_openlock-negative.stl)

### 5. Align the negative mod part

- Overwrite the position of the just added part by setting both it's x- and y-position to 0
- Align z-position to the ground by clicking the "Drop to bed" icon
   
![OpenLOCK Step 6](./img/openlock-step06.png)

It should now look like this:

![OpenLOCK Step 7](./img/openlock-step07.png)

### 6. Slice and double-check

Hit the "Slice now" button and double check the result:

![OpenLOCK Step 8](./img/openlock-step08.png)

![OpenLOCK Step 9](./img/openlock-step09.png)

### 7. Print it and have fun!

:smiley:


## Credits

All <a href="https://www.kickstarter.com/projects/segonefantasystl/segone-show-them-your-world-stl-and-pdf-fantasy-map" target="_blank">"Segone: show them your world (stl and pdf fantasy map)"</a> designs are copyrighted and the intellectual property of Simon Bertrand ("Stressed_Racoon" / "The Raccoon Brotherhood"):

<a href="https://www.kickstarter.com/projects/segonefantasystl/segone-show-them-your-world-stl-and-pdf-fantasy-map/creator_bio" target="_blank">Stressed_Racoo @ Kickstarter</a>

<a href="https://www.facebook.com/TheRaccoonBrotherhood" target="_blank">The Raccoon Brotherhood @ Facebook</a>

<br/>

The OpenLOCK system was created by [Printablescenery](https://www.printablescenery.com/product/open-lock/).

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Licensed under <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

The OpenLOCK system is used under the BSD license: [Printablescenery OpenLOCK license](https://www.printablescenery.com/2021/03/17/openvlex-2/)
