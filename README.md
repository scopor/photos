## 个人博客静态资源存储
* 某个文件：https://cdn.jsdelivr.net/gh/scopor/photos@main/资源文件, 例如https://cdn.jsdelivr.net/gh/scopor/photos@main/life/朱雀.jpeg


## 查看当前已有的静态资源JSON格式数据列表
* 方式一：https://data.jsdelivr.com/v1/package/gh/${username}/${repo}@main  有缓存，且很长时间不更新，比如部分文件的位置变动，该接口返回的还是旧数据
* 方式二：https://api.github.com/repos/${username}/${repo}/contents/  官方API，查看整个仓库的文件，JSON格式返回，也可以查询某个文件夹下面的，例如https://api.github.com/repos/scopor/photos/contents/life/

## 官方API列表
* https://api.github.com/repos/scopor/photos
