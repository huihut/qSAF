# SAF
SAF(Scan Angle Filter), a CloudCompare plugin, can filter the scanning angle in a range.

## CloudCompare

[CloudCompare](https://github.com/CloudCompare/CloudCompare)
 is an open source 3D point cloud and grid processing software that can handle all kinds of point cloud format data.

## SAF(Scan Angle Filter)

SAF(Scan Angle Filter) is a simple CloudCompare plugin that can filter a given range of scanning angles.

It is only suitable for LAS format point cloud file.

## Prerequisites

1. Install [CMake](https://cmake.org/) (3.0 or newer)

2. Install [Qt](http://www.qt.io/)  
  (CloudCompare 2.7 requires Qt version 5.5 or newer)

3. Make sure you have a C++11 compliant compiler (gcc 4.7+ / clang / Visual 2013 and newer)

*To compile the project with older versions of Qt (from 4.8 to 5.4) or with a non C++11 compliant compiler, you'll have to stick with the https://github.com/cloudcompare/trunk/releases/tag/v2.6.3.1 version*

## Usage

#### Put qSAF to CloudCompare

    mkdir CloudCompare
    cd CloudCompare
    git clone --recursive https://github.com/cloudcompare/trunk.git
    git clone https://github.com/huihut/qSAF.git trunk/plugins/qSAF
    rm -rf trunk/plugins/qSAF/.git

#### Generate / Run

[Generating CloudCompare project](https://github.com/CloudCompare/CloudCompare/blob/master/BUILD.md#generating-the-project)


## Screenshot

![SAFDlg](http://ojlsgreog.bkt.clouddn.com/SAFDlg.jpg)

<img src="http://ojlsgreog.bkt.clouddn.com/SAFDemo.jpg" width = "99%" />

## Tutorial

CloudCompare plugins and qSAF tutorial

1. [CloudCompare插件编写一（插件框架）](http://blog.huihut.com/2017/04/27/CloudCompareSAFPlugin_1_Framework/)
2. [CloudCompare插件编写二（数据结构）](http://blog.huihut.com/2017/04/27/CloudCompareSAFPlugin_2_DataStructure/)
3. [CloudCompare插件编写三（算法实现）](https://blog.huihut.com/2017/04/27/CloudCompareSAFPlugin_3_Algorithm/)

## License

[GNU v3.0](https://github.com/huihut/qSAF/blob/master/LICENSE)
