# 世界国家名称及国旗数据

####countries_list.json 文件
国家数据列表 [country_data, ...]

####countries_abb2.json 文件
以2位国家缩写为key的国家数据集合 {country_abb2 : country_data,  ...}

**country_data 国家数据**
```
{
	cn : 		国家中文名称
	en : 		国家英文名称
	full: 		国家英文全称
	abb2: 	国家英文2位简称（大写）
	abb3:	国家英文3位 简称（ 大写）
	code:	国家code数字（字符串）
}
```

####countries_flags 国旗图片文件夹
以国家英文2位简称为图片名的国旗图片，包含全部主流国家，缺少几个小众国家的国旗图片。
图片绝大部分宽640px