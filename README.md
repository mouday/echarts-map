# echarts-map

包含 echarts 用到的 map 地图文件

- github [https://github.com/mouday/echarts-map](https://github.com/mouday/echarts-map)

- gitee: [https://gitee.com/mouday/echarts-map](https://gitee.com/mouday/echarts-map)

## 文件目录

```bash
.
├── README.md
├── OutInquiry-mapData.js
├── echarts-for-weixin
│    └── js
│        └── wx-china.js
└── echarts-4.2.1-rc1-map
    ├── js
    │   ├── china-contour.js
    │   ├── china.js
    │   ├── province
    │   │   ├── anhui.js
    │   │   ├── aomen.js
    │   │   ├── beijing.js
    │   │   ├── chongqing.js
    │   │   ├── fujian.js
    │   │   ├── gansu.js
    │   │   ├── guangdong.js
    │   │   ├── guangxi.js
    │   │   ├── guizhou.js
    │   │   ├── hainan.js
    │   │   ├── hebei.js
    │   │   ├── heilongjiang.js
    │   │   ├── henan.js
    │   │   ├── hubei.js
    │   │   ├── hunan.js
    │   │   ├── jiangsu.js
    │   │   ├── jiangxi.js
    │   │   ├── jilin.js
    │   │   ├── liaoning.js
    │   │   ├── neimenggu.js
    │   │   ├── ningxia.js
    │   │   ├── qinghai.js
    │   │   ├── shandong.js
    │   │   ├── shanghai.js
    │   │   ├── shanxi.js
    │   │   ├── shanxi1.js
    │   │   ├── sichuan.js
    │   │   ├── taiwan.js
    │   │   ├── tianjin.js
    │   │   ├── xianggang.js
    │   │   ├── xinjiang.js
    │   │   ├── xizang.js
    │   │   ├── yunnan.js
    │   │   └── zhejiang.js
    │   └── world.js
    └── json
        ├── china-cities.json
        ├── china-contour.json
        ├── china.json
        ├── province
        │   ├── anhui.json
        │   ├── aomen.json
        │   ├── beijing.json
        │   ├── chongqing.json
        │   ├── fujian.json
        │   ├── gansu.json
        │   ├── guangdong.json
        │   ├── guangxi.json
        │   ├── guizhou.json
        │   ├── hainan.json
        │   ├── hebei.json
        │   ├── heilongjiang.json
        │   ├── henan.json
        │   ├── hubei.json
        │   ├── hunan.json
        │   ├── jiangsu.json
        │   ├── jiangxi.json
        │   ├── jilin.json
        │   ├── liaoning.json
        │   ├── neimenggu.json
        │   ├── ningxia.json
        │   ├── qinghai.json
        │   ├── shandong.json
        │   ├── shanghai.json
        │   ├── shanxi.json
        │   ├── shanxi1.json
        │   ├── sichuan.json
        │   ├── taiwan.json
        │   ├── tianjin.json
        │   ├── xianggang.json
        │   ├── xinjiang.json
        │   ├── xizang.json
        │   ├── yunnan.json
        │   └── zhejiang.json
        └── world.json
```

## 文件说明：

1、echarts-4.2.1-rc1-map 是 echarts 仓库下载的地图文件,版本号：4.2.1-rc1

[https://github.com/apache/echarts](https://github.com/apache/echarts)

2、echarts-for-weixin 是基于echarts/js/map.js, 仿照[echarts-for-weixin](https://github.com/ecomfe/echarts-for-weixin) 改造的地图数据

3、OutInquiry-mapData.js 是一份未编码压缩的 js 文件，来自项目：

[https://github.com/HilaryHA/OutInquiry](https://github.com/HilaryHA/OutInquiry)

## 说明：

echarts 仓库下载的 js 和 json 文件是压缩过的，所以看起来像是乱码，不过不影响使用。

## 下载使用

方式一：可以直接下载整个仓库

方式二：按需下载单个文件

eg: 源地址下载
```
wget https://raw.githubusercontent.com/mouday/echarts-map/master/echarts-4.2.1-rc1-map/js/china.js
```

镜像下载
```
wget https://ghproxy.com/https://raw.githubusercontent.com/mouday/echarts-map/master/echarts-4.2.1-rc1-map/js/china.js

wget https://cdn.jsdelivr.net/gh/mouday/echarts-map@master/echarts-4.2.1-rc1-map/js/china.js
```