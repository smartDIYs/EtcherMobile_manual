This section explains the parameter setting items.

<p align="center">
<img alt="UserOrigin" src="./images/parameter/about.png" style="width:50%">
</p>


## Speed
Set the moving speed of the laser head during processing (during laser irradiation). As the speed decreases, the energy of the laser given to the material increases.
```
※ It can be set in the range of 50-8000 [mm / min].
```

## Power
Set the intensity of laser irradiation. The greater the power, the greater the energy of the laser given to the material.
```
※ It can be set in the range of 0-100 [%].
```

## Number of times
Specify the number of times of laser processing. If a large amount of energy at one time adversely affects the material (melting or charring), repeated processing with small energy can be expected to improve the processing results.
```
※ It can be set in the range of 0-10 [times].
```

## DPI
This parameter is valid for raster processing. Set the definition when performing processing (dithering) to express the tone of the image. By default, 254 DPI is set, which is the value at which the laser is emitted every 0.1 mm. Also, unlike liquid crystal displays etc., the size of the laser irradiation point itself does not change even if DPI is raised. Please be aware that if you raise DPI too much the whole will be burned too much.

```
※ You can set in the range of 72-300 [DPI].
※ All the images below are engraved with the same image data and the same processing size.
※ It can be set individually according to the material characteristics or processing time efficiency.
```

Imprinted cardboard with FABOOL Laser Mini 3.5W / Use image: 1023x778 pixels

<p align="center">
<img alt="SmartScreen" src="./images/parameter/rasterDPI.jpg" style="width:70%">
</p>


## Hatching
This parameter is valid when processing a vector (painting) image. Hatching is a method of representing a surface by overlapping fine parallel lines, and is used to represent “filling” by laser processing. With hatching parameters, you can set the spacing between these parallel lines.
```
※ The interval can be set in the range of 0.05-3.0 [mm].
※ Text painting processing is also treated as vector (painting).
※ The impression of the processing result is different depending on the line width of the actual laser irradiation and the characteristics of the material.
```
