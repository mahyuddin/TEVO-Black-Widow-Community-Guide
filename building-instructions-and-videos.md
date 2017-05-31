# 2. Building Instructions and Videos

## 2.1 Video Links

There are excellent three set of BW build videos on YouTube. Each one of these is showing the build from a different perspective. <span style="color:green">It is strongly recommended that you watch all sets before starting to build your own</span>, and then follow one of them per your personal preference.

There is also an excellent series of videos, by Thomas Sanladerer, that each newbie should watch, as they explain the basics of 3d printing, and apply to any printer. These can be seen at [Tom’s Guides](http://www.youtube.com/playlist?list=PLDJMid0lOOYnRCAdbFfzECor3EbqF8euw).

### 2.1.1 Black Widow Assembly Video Series by Dean Walsh

[TEVO Black Widow Assembly Series](http://www.youtube.com/playlist?list=PLpGf9l-wO1ry6M2Z55NnX8bCmQ6LEky6o) \(8 videos\)

In addition, Extruder + Flow Rate Calibration, can be seen [HERE](http://www.youtube.com/watch?v=Gz8lieo0Nx8).

### 2.1.2 Black Widow Assembly Video Series by Pest Vic

[Everything TEVO Black Widow!](http://www.youtube.com/playlist?list=PLzvzDI0nZwjTXcTe7n32hQNmCUdO9Vrm-) \(13 videos\)

### 2.1.3 Black Widow Version 3 Assembly Video Series by Ruiraptor

[TEVO Black Widow Version 3 Assembly Series](http://www.youtube.com/playlist?list=PLY5Z2koT4Mi4JoQ_QZDS7pu9S1m0SqUiB)

## 2.2 How to square & parallel the frame and leadscrews?

The document, can be found at Annex section 13.2 of this document.

## 2.3 Gift Parts

<table>
  <tbody>
    <tr>
      <td style="text-align:center; width:50%"><img src="assets/TEVO BW thermistor.png" alt="thermistor"></td>
      <td style="text-align:left; width:50%">With your kit you receive two items as a gift. One item is a thermistor for the hot-end heatblock. <br><br><p style="color:green"> <b style="text-decoration: underline;">Please note</b><br> This thermistor can't be used on the heat-bed, as is, since the heat-bed uses an SMD (Surface Mount Device) type thermistor. If you need to use it for the heat-bed, refer to Section 10.2.3 for instructions.</p>The other item is two LED (Light Emitting Diode) strips which you can connect directly to the 24 VDC (Volt Direct Current) of the Power Supply Unit. If they do not work check the polarity. There have been reports that the polarity signs on the strip were wrong. So double check.</th></td>
    </tr>
  </tbody>
</table>

## 2.4 XYZ Proximity Sensors Adjustment

The X Y and Z sensors are proximity inductive sensors which sense metal. To get them working properly adjust them at a very close distance (maximum 1mm) to the part that should activate it. The sensors have a small orange LED built-in. When the sensor is activated the orange LED is ON. You can use a tip of a screw driver to test the sensor for working.

## 2.5 Z bottom and top plate bearing fitting not correct

<table>
  <tbody>
    <tr>
      <td style="text-align:center; width:50%"><img src="assets/z plate bearing fitting 01.png" alt="Fitting z plate bearing">
      <img src="assets/z plate bearing fitting 02.png" alt="Fitting z plate bearing">
      <img src="assets/z plate bearing fitting 03.png" alt="Fitting z plate bearing">
      <img src="assets/z plate bearing fitting 04.png" alt="Fitting z plate bearing">
      </td>
      <td style="text-align:left; width:50%">
      If you experience play on bearings, use the
following tip.<br><br>
Use regular thin paper and glue with a little bit of glue stick glue the piece to the outer race of the bearing and with care slide both in place. All depends on the play. When ready remove the paper remains not needed. If you experience such play you can use this trick temporary and file a support ticket at TEVO for a
correct version.<br><br>
<b>Bearing type:</b> MR688ZZ, <b>ID:</b> 8mm; <b>OD:</b> 16mm;<br>
<b>Width:</b> 4mm.<br><br><p style="color:green"> <b style="text-decoration: underline;">
Please note</b><br>
Some suffixes, e.g. ZZC have 5mm width. They
might fit, however this has not been verified.</p></td>
    </tr>
  </tbody>
</table>

## 2.6 E3D-V6 Hot-end & Bowden Tube Assembly
Assembly instructions can be found here: [http://wiki.e3d-online.com/wiki/E3D-v6_Assembly](http://wiki.e3d-online.com/wiki/E3D-v6_Assembly)

<span style="text-decoration: underline;">The Stock V3 Hot-end breakdown is as follows:</span>

<b style="color:green">A) Heat-sink: Modified E3D-V6.</b>
- The J-Head and the fins are the same as E3D-V6, however the thread for the heat-break is M6, not M7.

<b style="color:green">B) Heat-block: Modified E3D-V5.</b>
- Different dimensions. An E3D-V5 heat-block may not function properly, thermal-wise.

<b style="color:green">C) Heat-break: Modified E3D-V5.<b>
- Longer by 1mm.
- Actually for 3mm filament, fited with 3mm OD, 2mm ID PTFE liner (PTFE: Poly-TetraFluoro-Ethylene, known as Teflon).

<b style="color:green">D) Nozzle: Modified MK7.</b>
- The nozzle is not from the E3D family.
<table>
  <tbody>
    <tr style="text-align:center"><img src="assets/BW Extruder and Stock-v3 Hotend General.png" alt="BW Extruder and Stock-v3 Hotend"></tr>
    <tr>      <b>Figure #1:</b> TEVO Black Widow Stock Extruder and Stock V3 Hot-end    </tr>
    <tr>      It is recommend for anyone who has one of it’s components faulty, to do the following:<br><br>
    <ol>
<li>Get replacement parts from TEVO. Getting replacement parts from other vendors would be extremely difficult, if not impossible on one hand, and trying to use the originals/clones won’t work, as most probably they won’t fit, or not work properly thermal-wise.</li>
<li>Replace the TEVO Stock-V3 with either a genuine E3D-V6, or a good clone, as depicted in the following <b>Figures #3 & #4</b>.</li>    </ol></tr>
  </tbody>
</table>
<br><br>
<table>
  <tbody>
    <tr style="text-align:center"><img src="assets/BW with Stock-v3 Hotend Cross-Section.png" alt="BW Stock-v3 Hotend Cross-Section"></tr>
    <tr><b>Figure #2:</b> TEVO Black Widow Stock-v3 Hotend Cross-Section</tr>
    <tr><br> One of the most common errors, when assembling the hot-end, which is the #1 cause for leaks and clogs, is the way the nozzle is assembled with relations to the heat-block and heat-break.<br><br>
The nozzle must be locked to the heat-break, not the heat-block, as depicted in <b>Figure #2</b> above.<br><br>
When locking the nozzle to the heat-block, a gap is formed between the nozzle and the heat-break. (<b style="color:green">The gap is exaggerated in the figure, to enhance readability</b>) This gap will let the high-pressure molten filament to flow between the threads, and will start leaking at the top of the heat-block. In some cases,depending on manufacturing tolerances, it may leak from the bottom of the heat-block as well.<br><br>
If the gap is large enough, the rapid temperature changes during retractions, will eventually cause it to clog.</tr>
  </tbody>
</table>
<br><br>
<table>
  <tbody>
    <tr style="text-align:center"><img src="assets/BW with E3D Extruder and Hotend.png" alt="BW with Stock Extruder and E3D-V6 Hot-end"></tr>
    <tr>      <b>Figure #3:</b> TEVO Black Widow with Stock Extruder and E3D-V6 Hot-end</tr>
    </tbody>
</table>
<br><br>
<table>
  <tbody>
    <tr style="text-align:center"><img src="assets/BW with E3D Hotend Cross-Section.png" alt="E3D-V6 Hot-end Cross-Section"></tr>
    <tr>      <b>Figure #4:</b> E3D-V6 Hot-end Cross-Section Views</tr>
    </tbody>
</table>
##2.7 Recommended prints to start with
Parts you might like to print to enhance the machine performance at start up.




















