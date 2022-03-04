# phen
# The models of six methods for extracting vegetation phenophases (i.e. start of season(SOS) and end of season (EOS))

# Run requirements and Usage description

## The following is a brief description of the operating environment and conditions of the program.

## 1) The program must run on Linux
## 2) The C++ of g++ 5.4 is preferred
## 3) GDAL must be installed
## 4) You need to prepare a TIF (INT16 format) with 46 issues (one year time series). For details, see lc08_024035_2_01.tif.
## 5) Operation Mode After entering the root directory of the program, run it in the following way:
### ./open_MP_EOS LC08_024035_2_01.tif eos. tif #(Run EOS program, lc08_024035_2_01.tif sample data, eos.tif output data)
### ./open_MP_SOS lc08_024035_2_01.tif sos. tif #
## 6) The program can be called in batches through the.sh text to copy data to the output path
### ./sos1.sh #(program to run EOS)
### ./eos1.sh #
## 7) EOS. Tif is the result of phenology. Contains 6 layers, 6 phenology results. The results correspond to the 6 algorithms in the following table:
### 

# Result maps
## 

## 




