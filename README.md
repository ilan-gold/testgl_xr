# testgl_xr
A quick demo of getting an image tile of high bit-per-channel depth and rendering it in WebGL, using the logic that will be used in vitessce.  This is a very dirty example with extraneous code, but for now it is fine.  Edit the `max_val` and `min_val` parameters to
change the range.  The initial `x`, `y`, `z` and `tileSize` control tile-specific paramters.  Once [zarr.js](https://github.com/gzuidhof/zarr.js/) ships with the extra data types, the cast to 32 bits on line 88 won't be necessary and you can serve the data directly, but for now this demos the range mapping.  
# Demo
Just open the file in your browser.
