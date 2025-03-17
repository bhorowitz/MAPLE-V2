#MAPLE V2

Lyman Alpha power spectra estimation in 3d, prototype based on MAPLE. Right now it is a combination of various disorganized scripts...

Workflow is roughly as follows:

1) If you don't already have a "configuration" (see configs folder) run get_config.py with the options you want.
2) If you don't already have a fiducial power spectra, make one (see gen_fid.ipynb for example).
3) Run p3-manual.ipynb.
4) While p3-manual is running, it will generate a "example_gen_field.py" file. It is probably worth your time to double check this file has the same powerspectra as your input into gen_fid by running the test_power.ipynb file.