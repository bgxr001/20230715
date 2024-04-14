### #标题修饰符，修饰符与正文之间必须有空格
# #表示一级标题
## ##二级
### ###三级
#### ####四级

## 正文内容，直接编辑正文即可，但是换行使用\<br\>,如果在数据前加入两个空格，则是分段
测试的文本内容，第一行<br>
第二行
  分段测试
## 正文特效，\*斜体\*,\*\*粗体\*\*,\*\*\*粗斜体\*\*\*,\`凸显特效\`,~~删除线特效~~

  *特殊字体，斜体*<br>
  **特殊字体，粗体**<br>
  ***特殊字体，粗斜体***<br>
  凸显效果，文本中显示`关键字`<br>
  ~~一段删除线特效~~

### \-\-\-\-分割线效果
----
### 引用 \> 引用效果
>一级引用
>>二级
>>>三级
>>>>四级
### 列表，有序列表，无序列表，可以互相混合使用
#### 无序列表
* FPS射击游戏
  * cf
  * cs
    * csgo1.0
    * csgo2.0
* 动漫风格游戏
  * 原神
  * 明日方舟
* 竞赛类游戏
  * wrc
  * 地平线
####有序列表
1. 计算机组成
   1. CPU
   2. 内存
   3. DISK
2. 数据库
   1. redis
   2. Mysql
   3. oracle

###表格样式 --|:居左 --:居中 |--:居右
|姓名|年龄|技能|武力值|
--|:--:|--:|--:
|刘备|44|仁德|68|
|关羽|38|武圣|98|
|张飞|35|咆哮|89|
|界徐盛|32|破军|100|

### 超链接 \[\超链接标题\](链接地址"悬停标题")
[哔哩哔哩](https://www.bilibili.com"B站")

### 插入图片\!\[\图片标题\](图片地址"悬停标题")
#### 如果插入的图片为磁盘路径，无法正确显示，需要将图片上传到图床中，而后生成对应的url网络地址才可以
![流程图](D://UserFile//Desktop//个人//运动会.drawio.png"流程图")
###插入代码片段 ```语言 ```
```cpp
#include<iostream>
using namespace std
int main(){
cout<<"hello githib"<<endl;
return 0;
}
```

