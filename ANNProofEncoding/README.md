Theorem 1 from NFM2025 is encoded at line 217 of UTPANNProofs.thy.

The verification condition for Marabou are encoded at line 311 of UTPANNProofs.thy.

We encode ANNController as CircANN at line 214, and StandardController as CyclicRCController at line 23 of UTP_ANN_Defs.thy 

We encode our pattern for describing HiddenLayers || OutputLayer, supporting the definition of ANNController, 
at line 209 of UTP_ANN_Defs.thy.

In the directory `Marabou_Scripts` we have a shell script that automates conformance proof between AnglePID and AnglePIDANN: `anglepid_conformance_testing.sh`.

We have also included a log of a succesful run in `anglepid_conformance_testing.txt`.
