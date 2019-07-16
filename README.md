[English](README_en.md)
# 虚拟--gps
转自：https://steppark.net/15294912961206.html
-----------------
配置一个 GPX 格式的文件：这个文件稍后会导入到 Xcode 项目中使用，文件内容如下，注意将其中的 lat 和 lon 改成刚刚你获取到的 WGS-84 坐标。
<?xml version="1.0" encoding="UTF-8" ?>
<gpx version="1.1"
    creator="GMapToGPX 6.4j - http://www.elsewhere.org/GMapToGPX/"
    xmlns="http://www.topografix.com/GPX/1/1"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.topografix.com/GPX/1/1 http://www.topografix.com/GPX/1/1/gpx.xsd">
    <wpt lat="31.23555959" lon="121.50097295">
    </wpt>
</gpx>
