# PropRes_Sender

This stack modifies BACnet opensource stack (http://bacnet.sourceforge.net/). It implements propotional response for BACnet WP messages on analog output objects. This is the code on the WP sender side.

# How to run the code
- ReadProp: $ demo/readprop/bacrp

bacrp device-instance object-type object-instance property [index]

./bin/bacrp 1234 1 0 85


- WriteProp: $ demo/writeprop/bacwp

bacwp device-instance object-type object-instance property priority index tag value [tag value...]

 ./bin/bacwp 1234 1 0 85 16 -1 4 100
