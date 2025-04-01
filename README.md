# Aria2-Trackers
## 自动获取tracker文件并转换为Aria2可用格式
国外：https://tk.sleele.com

国内：https://sleele.gitee.io/aria2-trackers/

### 另外推荐一下我制作的docker-aria2  
支持自动更新trackers及诸多扩展功能  
目前唯一支持自定义二级或多级目录的docker-aria2  
https://github.com/SuperNG6/docker-aria2  
https://hub.docker.com/r/superng6/aria2  

## 2020.10.15日更新

        1、将数据源地址更改为jsdelivr cdn地址，现在国内访问速度大大提升，应该不会再出现无法获取trackers的情况了
        2、添加XIU2/TrackersListCollection trackers数据源，推荐使用，tracker数量更多，且更符合国情，包含更多国内站点

Aria2下载BT和磁力经常会遇到没有速度这个问题，配置Trackers可以很大程度减少这种情况，并且可以加快BT下载速度，由于ngosang/trackerslist https://github.com/ngosang/trackerslist 给出的list Aria2是不能够直接解析的，需要稍作处理，于是便有了此工具，此工具基于kooolshare论坛的'898028948'释放的源码制作（http://koolshare.cn/forum.php?mod=viewthread&tid=139749&highlight=Trackers ），不过由于源码没有完全放出，无法运行。我做了一些补充完善，使之可以正常运行


使用教程：https://sleele.com/2019/05/12/aria2-trackers/
![Xnip2020-10-15_15-37-37](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/2020-10-15/Xnip2020-10-15_15-37-37.png)
