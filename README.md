![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)  

[中文](https://github.com/hehuapei/visitor-badge/blob/master/readme_cn.md)

#### Project Home
> [https://visitor-badge.laobi.icu](https://visitor-badge.laobi.icu)

#### Usage
```
Simple: 
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=keyword)

change title: 
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=keyword&title=viewers)

```

#### Feature

- **2020.07.18**  
1. You can use parameter 'title' to change badge's title！  
**tips: The title Poor compatibility to chines**  
Official: [link](https://pypi.org/project/pybadges/)  
pybadges uses a pre-calculated table of text widths and kerning distances (for western glyphs) to determine the size of the badge. So Eastern European languages  may be rendered less well than Western European ones:  
and glyphs not present in Deja Vu Sans (the default font) may be rendered very poorly:  
pybadges does not have any explicit support for languages that are written right-to-left (e.g. Arabic, Hebrew) and the displayed text direction may be incorrect:  
 
- **2020.07.17**  
1. Change count-api to my own service, optimize the counting speed.   
2. It facilitates later functions (data analysis, data backup, etc.)

#### Fork From
> jwenjian: [https://github.com/jwenjian/visitor-badge](https://github.com/jwenjian/visitor-badge)
