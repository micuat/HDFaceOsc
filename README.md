HDFaceOsc
========

Send KinectV2 HDFace info through osc - work in progresss.


Format
--------

* Address: `/osceleton2/hdface`
* Vertices stored as a byte-array blob:
    * `float* x = (float*)(blob + i * 4 * 3 + 0);`
    * `float* y = (float*)(blob + i * 4 * 3 + 4);`
    * `float* z = (float*)(blob + i * 4 * 3 + 8);`

Todo
--------

* add tracking id
* add face features
* non-c-pointer dependent storage (?)
