LWLab 7-way wire harness
========================

After working on the 4-way design, now I'm extending it to 7 SQUID cards to see if it is possible to make it work. The strategy will be:

1. Extend stages 1-4 by 0.5 inches per SQUID card
2. Modify the geometry of stage 3 in order to fit within the ISO200 inner diameter

To first order, the expected clearance will be `2 mm`. 

According to http://literator.colin.merkel.is/do7uO, the clearance will be `-4 mm` before removing `6 mm` of shoulder on the 50 K stage (stage 3). But this is making a number of simplifying assumptions about the geometry. It may also be necessary to change the geometry of the previous stage. Finally, rather than building a faceplate, it may make sense to use the entire 8-inch outer flange as the basis for Stage 5, reducing the room required for bolts.

LWLab 4-way wire harness
========================

These are the SolidWorks files for the redesigned wire harness, which came from the original 3-way design. 

The main changes that have been implemented since that version are:

1. Stages 1-4 were widened by 0.5 inches to accomodate an additional PCI slot and SQUID card
2. Stages 2-3 were expanded vertically by 0.54 inches to give extra space for the 6.25 inch SQUID cards.

## Important parameters

The clearance between the inner diameter of the ISO200 port and stage 3 is `6.8 mm`

Refer to http://literator.colin.merkel.is/do7uO for calculations of the clearance for more than 4 cards.
