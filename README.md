# FRCScout
An HTML based scouting app for FRC competition

This can be edited to create a custom form for scouting at FRC competitions.
The primary function of this is to have a bunch of user inputs and a submit button,
when the user submits their data a QR code is generated with text in CSV format,
which can then be read by a scanner and transfered into any database that can take
CSV input. The order of data in the CSV is customized. This is the end-user part of
the solution for a cheap, reliable, and efficient digital scouting system.

Inside the code all you have to edit is the HTML inputs (AKA your scouting questions) inside the HTML Body. You will also need to then define your new HTML inputs in the data array section of the javascript. Everything else should be able to remain the same.
