## OpenCV C++ Stereo Camera Calibration

From https://github.com/sourishg/stereo-calibration.

### Dependencies

- OpenCV
- popt

### Compilation

Compile all the files using the following commands.

```bash
mkdir build && cd build
cmake ..
make
```

### Run

Modify run.sh to run the calibration.

```bash
-n number of images
-L path to the left camera images
-R path to the right camera images
-o file containging calibration results 
-l -r prefix of the images, following by 1, 2, 3, ...
-e postfix (e.g., .png)
```
