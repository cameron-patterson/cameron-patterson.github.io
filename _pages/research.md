---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

# Space Weather Impacts on Railway Signalling Systems in the United Kingdom

## Railway Signalling

Using **insulated rail joints (IRJs)**, a railway line is split into multiple smaller isolated sections called 'blocks'. Each block is connected to its own signalling system, called a **track circuit**, that will indicate whether that block is clear or occupied to train drivers in preceding sections.

In some electrified railways, only one of the rails will have IRJs, this is due to locomotives needing a continuous path for current to flow from the external power supply to the train and then back to the supply to complete the circuit and power the train; in this case, the rail with the IRJs is called the **signalling rail** and the continuous rail is called the **traction rail** (as it carries the traction return current).

<img src="/images/blocks.png">
<centre> <em> Diagram showing how insulated rail joints split a railway line into individual track circuits, each one controlling the signalling system for that block. </em> </centre>

## Track Circuits

Each block in a railway line has a signalling system controlled by a track circuit. A power supply is connected to the side of the circuit from which the train enters (left) and an accompanying resistor to protect it from short circuiting; the relay is on the far end of the block (right), formed of resistors and an electromagnet which in (a) is **energised** by the power supply, causing the switch to be in the configuration to display a **green light**, indicating the section is **clear**.

When a train enters the block, as in (b), the wheels and axle short circuit said power supply causing the electromagnet to be **de-energised**, the switch falls to the configuration that displays a **red light**, indicating the section is **occupied**.

A **geomagnetic storm** can generate **induced currents** in the ground which flow though the grounded conducting rails and interfere with the normal operation of a track circuit. If sufficiently strong, these currents can de-energise and energised relay, showing a clear block as occupied, leading to **delays**, or the far more hazardous case of energising a de-energised relay, displaying a clear signal for an occupied section, potentially leading to a **collision**.

<img src="/images/1a. green-1.jpg">
<img src="/images/1b. red-1.jpg">
<centre> <em> Circuit diagram of a railway signalling track circuit for a single block along a network in the cases of (a) the absence of a train in the block and (b) a train occupying the block. </em> </centre>

## Railways in the UK

When investigating the impacts of space weather on UK railway signalling systems, we will consider two sections of the UK network: (A) the 74 km **Glasgow to Edinburgh via Falkirk** line and (B) a 34 km portion of the West Coast Main Line from **Preston to Lancaster**; both are electrified using 50 Hz AC at 25 kV. The two sections were selected for their different orientation (east-west for A and north-south for B) and different geological terrane.

For section B, even though we are only analysing the impacts of track circuits between Preston and Lancaster, the majority of the West Coast Main Line is connected with a continuous traction rail, this means that we need to consider those track circuits outside our area of interest as well.

<img src="/images/2. line_maps-1.jpg">
<centre> <em> A geographic map of a northern portion of the United Kingdom showing both chosen railway lines with areas of interest highlighted and enhanced (top right and bottom right) to show the locations of signals. The top line (blue) is the Glasgow to Edinburgh via Falkirk line, stretching in an east-west orientation; the bottom line (red) is a potion of the West Coast Main Line from Preston to Lancaster, with the extension beyond those sections displayed opaquely, stretching in a north-south orientation. </em> </centre>

## Right-side Failures

When a track circuit relay that is supposed to be energised is de-energised due to a fault or other reason, it is considered a 'right-side failure', this is due to the relay failing in a manner that is safe, as drivers will be indicated to stop and wait and will not pass into that section until the control centre can notify them of the situation.

Right-side failures can be caused by space weather if the geomagnetically induced currents are strong enough to oppose the charge of the power supply.

Assume there are no trains occupying any of the blocks and consider a case where there is no geomagnetic storm and hence no geoelectric field, E, to induce currents in the ground, we see that all relays function normally, each one displaying a green/clear signal.

<img src="/images/8. zero-1.jpg">
<centre> <em> For no geoelectric field: the currents through each of the track circuit relays between Preston and Lancaster (left) and Glasgow to Edinburgh (right) with no geoelectric field applied, the blue dots indicate the current level and the dashed red line shows the threshold below which the track circuit would de-energise and fail to operate correctly. Below each plot is a schematic view of each signal and whether it is operating correctly, an unfilled green dot means normal operation and a filled red dot indicates a failure. </em> </centre>  

<p><br />However, once we apply a geoelectric field to the sections, we see the currents across the relays start to change: for Glasgow to Edinburgh, there are signal failures at all geoelectric field strengths shown, with the fewest occurring at 2 V/km (5 failures) and the most occurring at -4 V/km (29 failures); for Preston to Lancaster, the signals all operate normally until a geoelectric field of -4 V/km is applied, causing 9 of the relays to fail. </p>

Preston to Lancaster has a higher tolerance due to it being near the centre of a much longer line. As is shown in Glasgow to Edinburgh, the relays towards the ends of the line fail at lower E values than the centre.

<img src="/images/10. ge_non_zero-1.jpg">
<centre> <em> Same as above, but for Glasgow to Edinburgh with different magnitudes and directions of geoelectric field applied. </em> </centre>

<p><br /></p>

  <img src="/images/9. pl_non_zero-1.jpg">
<centre> <em> Same as above, but for  Preston to Lancaster. </em> </centre>

## Wrong-side Failures

When a track circuit relay that is supposed to be de-energised is energised, it is considered a 'wrong-side failure', this is a far more hazardous scenario, as drivers will not be indicated to stop even if there is a train occupying a section up ahead. However, there are usually secondary systems in place to detect the presence of a train in a block, so control centres can alert drivers to the signal issue.

The potential for space weather to cause wrong-side failures is something I am currently working on, so please do check back at a later date as I will continually update this page as my research progresses.

# Thanks for reading!
