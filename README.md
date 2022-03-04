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
![Image don't exsit!](https://github.com/ruanyj5/phen0/blob/main/Algorithm%20Introduction%20.jpg)

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

***This small program is jointly completed by academician Ruan Yongjian, Xin Qinchuan, Zhang Xinchang, Jiang Xin. 
It is only published for users' scientific research. 
If any scientific research team needs to refer to this program, please add the reference of this article in the reference literature, which is also published on the website, thank you very much!***


**-------------------中文介绍------------------**
# 植被物候期的6种提取方法模型(季节开始和季节结束)
# 使用说明

## 以下是程序的简单运行环境与条件说明。
## 1) 程序必须在linux 系统下运行
## 2) 最好是g++ 5.4 以上的C++版本
## 3) 必须安装GDAL
## 4) 需要准备好一个包含46期影像(一年的时间序列)的tif （int16格式的，详细参考示例数据 LC08_024035_2.tif ）
## 5) 运行方式 进入程序根目录后，用以下方式运行：
### ./open_MP_EOS LC08_024035_2.tif  EOS.tif   #(运行EOS的程序  ，LC08_024035_2.tif 示例数据，EOS.tif  输出数据 )
### ./open_MP_SOS LC08_024035_2.tif  SOS.tif  #(运行SOS的程序 )
## 6) 可以通过.sh 文本批量调用程序，将数据拷贝到output路径下
### ./sos1.sh #(运行EOS的程序 )
### ./eos1.sh #(运行SOS的程序 )
## 7) EOS.tif  是物候的结果。包含6个图层，6种物候的结果。结果分别对应以下表格的6种算法：
![图片不存在!](https://github.com/ruanyj5/phen0/blob/main/Algorithm%20Introduction%20.jpg)

# 结果图

## 250m分辨率美国本土地区8种不同的植被生长SOS图（250 m resolution mapping of land surface phenology across conterminous United States）.jpg
![图片不存在!](https://github.com/ruanyj5/phen0/blob/main/250m%E5%88%86%E8%BE%A8%E7%8E%87%E7%BE%8E%E5%9B%BD%E6%9C%AC%E5%9C%9F%E5%9C%B0%E5%8C%BA8%E7%A7%8D%E4%B8%8D%E5%90%8C%E7%9A%84%E6%A4%8D%E8%A2%AB%E7%94%9F%E9%95%BFSOS%E5%9B%BE%EF%BC%88250%20m%20resolution%20mapping%20of%20land%20surface%20phenology%20across%20conterminous%20United%20States%EF%BC%89.jpg)
## 30m分辨率美国本土地区8种不同的植被生长SOS图（30 m resolution mapping of land surface phenology across conterminous United States）.jpg
![图片不存在!](https://github.com/ruanyj5/phen0/blob/main/30m%E5%88%86%E8%BE%A8%E7%8E%87%E7%BE%8E%E5%9B%BD%E6%9C%AC%E5%9C%9F%E5%9C%B0%E5%8C%BA8%E7%A7%8D%E4%B8%8D%E5%90%8C%E7%9A%84%E6%A4%8D%E8%A2%AB%E7%94%9F%E9%95%BFSOS%E5%9B%BE%EF%BC%8830%20m%20resolution%20mapping%20of%20land%20surface%20phenology%20across%20conterminous%20United%20States%EF%BC%89.jpg)

# 引用

## 如果需要使用这个编码文件, 我们希望原始文献能够得到引用:
```
@article{roy2021attention,
     标题={A method for quality management of vegetation phenophases derived from satellite remote sensing data},
     作者={Yongjian Ruan, Xinchang Zhang, Qinchuan Xin, Ying Sun, Zurui Ao and Xin Jiang},
     期刊={International Journal of Remote Sensing},
     年份={2021},
     发布={International Journal of Remote Sensing}
     }
```
# 文献网址:
![文献网址](https://github.com/ruanyj5/phen0/blob/main/2021_A%20method%20for%20quality%20management%20of%20vegetation%20phenophases%20derived%20from%20satellite%20remote%20sensing%20data.pdf)

# 使用需知

***此程序由阮永俭、辛秦川、张新长、江鑫合作完成，发布仅供用户科研使用，若有科研团队需参考此程序内容，烦请在参考文献中加入此文的引用，参考文献亦发布在网站，十分感谢！***
