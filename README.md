# ExcelUtils

POI实现Excel文件读写(导入导出)操作工具类

###需要添加的依赖
```xml
<dependency>
    <groupId>javax.servlet</groupId>
    <artifactId>servlet-api</artifactId>
    <version>2.5</version>
</dependency>
```
```xml
<dependency>
    <groupId>org.apache.poi</groupId>
    <artifactId>poi-ooxml</artifactId>
    <version>3.9</version>
</dependency>
```

###导入导出Excel
- 单个sheet， 数据集类型是List<List<Object>>
- 单个sheet， 数据集类型是List<Object[]>
- 多个sheet， 数据集类型是List<ExcelSheet<List<Object>>>
- 多个sheet， 数据集类型是List<ExcelSheet<List<Object>>>
- 多个sheet， 数据集类型是List<ExcelSheet<List<Object>>>, 支持大数据量


