# Simple Circular Queue
This code targets the RP2040's mutex functionality to avoid a race condition 
between using the queue between its two cores. 
It defaults to non thread safe version that doesn't require any 
external libraries besides ```stdlib.h```.

Use the build flag ```SCQ_RP2040_MUTEX``` to enable 
the RP2040 thread safe operation.