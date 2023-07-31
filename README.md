# VVC_Calculator

This is a simple desktop app for calculating heat losses to return joints
at the end of a Hot potable water system.
This App uses a non-oficial manual calculation method that sums the length
of all pipes leadfeedinging a return joint.
In this calculation each pipe's length is divided by the total number of
all the return joints it feeds.
All these divided lengths are summed up together and is multiplied by a 10 Kwh which
is a rough estimation of heat loss per length of (hot water + return hot water) pipe.
The result is the hea loss that can be added to MagiCAD's return joint data.
