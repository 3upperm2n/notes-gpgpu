# notes-gpgpu
gpgpu notes

### People
* http://people.maths.ox.ac.uk/gilesm/cuda/



### Programming Feature
##### DP
There is also a hardware limit on maximum nesting depth, and thus synchronization depth; 
as of Compute Capability 3.5, the hardware limit on depth is 24 levels.

By default, space is reserved for 2048 pending child grids; 
this can be extended by setting the appropriate device limit, as in the following code.
[link] (https://devblogs.nvidia.com/parallelforall/cuda-dynamic-parallelism-api-principles/)
