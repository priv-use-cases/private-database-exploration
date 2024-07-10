# Private Functional Exploration over Large Datasets
Code for TETRIS: Priva-t-e Functional -E-xplora-t-i-on over La-r-ge Data-s-ets 

## To run the code
in src:
$ go test -v -run=PDE -timeout=0

## Setup
This code requires ~22GB of RAM to run with 128-bit secure parameters.
You can change the paramaeters LogNPack and LogNEval in the file parameters.go, 
this will run the code with insecure parameters but will require less memory 
and bandwidth.
The test will pring the LogN, LogQP and key distribution of each parameter.

## Client, Server and Circuit
The client and server steps together with the computation circuits are detailed in 
Section "E. Putting Altogether" of the submitted paper.

