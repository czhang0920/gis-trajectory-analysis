# gis-trajectory-analysis
An exploratory analysis of courier GIS trajectory data

Data input: GIS trajectory (update every 2 seconds) of courier men and delivery shipment orders
Purpose: gain insights of the behaviors of courier men in the current practice so as to calibrate the simulation model for modeing the logistics operations
Methodology:
-- Adjustment of delivery sequence: K nearest neighbor regression with K=1
-- Inference of the average service time per stop: formulate as a generalized N-body problem (GNBPs) and then apply the K nearest neighbors search using Ball tree in sklearn

