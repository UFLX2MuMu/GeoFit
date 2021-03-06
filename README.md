# GeoFit
GeoFit corrections: Analytical corrections to the momentum scale of prompt muons for Run2


## Usage:

The GeoFit corrections depend on the *pT*, *eta*, and *d0* and they are provided separately for each year of Run 2 data taking.

The inputs to the PtCorrGeoFit function should be the *pT* of the muon after Rochester corrections, *eta* of the muon, *d0* value of the muon with respect to the Beam Spot multiplied by the muon charge, and finally the year of the data/MC sample.

*PtCorrGeoFit(d0_BS_charge, pt_Roch, eta, year)*

The output of this function is the corrected muon *pT*. 
