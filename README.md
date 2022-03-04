# Phenology

# The models of six methods for extracting vegetation phenophases (i.e. start of season(SOS) and end of season (EOS))

# Usage description

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

## 250m分辨率美国本土地区8种不同的植被生长SOS图（250 m resolution mapping of land surface phenology across conterminous United States）.jpg
![Image don't exsit!](https://github.com/ruanyj5/phen0/blob/main/250m%E5%88%86%E8%BE%A8%E7%8E%87%E7%BE%8E%E5%9B%BD%E6%9C%AC%E5%9C%9F%E5%9C%B0%E5%8C%BA8%E7%A7%8D%E4%B8%8D%E5%90%8C%E7%9A%84%E6%A4%8D%E8%A2%AB%E7%94%9F%E9%95%BFSOS%E5%9B%BE%EF%BC%88250%20m%20resolution%20mapping%20of%20land%20surface%20phenology%20across%20conterminous%20United%20States%EF%BC%89.jpg)
## 30m分辨率美国本土地区8种不同的植被生长SOS图（30 m resolution mapping of land surface phenology across conterminous United States）.jpg
![Image doesn't exsit!](https://github.com/ruanyj5/phen0/blob/main/30m%E5%88%86%E8%BE%A8%E7%8E%87%E7%BE%8E%E5%9B%BD%E6%9C%AC%E5%9C%9F%E5%9C%B0%E5%8C%BA8%E7%A7%8D%E4%B8%8D%E5%90%8C%E7%9A%84%E6%A4%8D%E8%A2%AB%E7%94%9F%E9%95%BFSOS%E5%9B%BE%EF%BC%8830%20m%20resolution%20mapping%20of%20land%20surface%20phenology%20across%20conterminous%20United%20States%EF%BC%89.jpg)

# Citation

## If you use this code in your research, we would appreciate a citation to the original paper:
```
@article{roy2021attention,
     title={A method for quality management of vegetation phenophases derived from satellite remote sensing data},
     author={Yongjian Ruan, Xinchang Zhang, Qinchuan Xin, Ying Sun, Zurui Ao and Xin Jiang},
     journal={International Journal of Remote Sensing},
     year={2021},
     publisher={International Journal of Remote Sensing}
     }
```
## Here is the paper URL:
![Paper URL](https://github.com/ruanyj5/phen0/blob/main/2021_A%20method%20for%20quality%20management%20of%20vegetation%20phenophases%20derived%20from%20satellite%20remote%20sensing%20data.pdf)

# Requirements

***
This small program is jointly completed by academician Ruan Yongjian, Xin Qinchuan, Zhang Xinchang, Jiang Xin. 
It is only published for users' scientific research. 
If any scientific research team needs to refer to this program, please add the reference of this article in the reference literature, which is also published on the website, thank you very much!
***
