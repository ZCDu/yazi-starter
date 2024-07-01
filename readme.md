# yazi食用手册
yazi主要有三个配置文件
keymap.toml 键位配置
yazi.toml 配置各个应用默认的打开软件
theme.toml 主题配置
# 默认软件配置
## 编辑器
通过$ehco $EDITOR$查看，在arch下，我们可以通过在bash的配置增加`export EDITOR=nvim`来修改

# 推荐插件
让l实现既能进入子目录，也能用于打开文件，[Smart enter](https://yazi-rs.github.io/docs/tips)
[keyjump.yazi](https://yazi-rs.github.io/docs/resources): 类似于vim里的快速移动
[Show symlink in status bar](https://yazi-rs.github.io/docs/tips): 需要先复制指定的内容到yazi/init.lua，然后重写这个方法


# 友情出演
参考B站UP，[夜未央-天将亮](https://www.bilibili.com/video/BV1S6421T7BD/?spm_id_from=333.788&vd_source=b4feeb49d56b01c36b710ef8dc1b9ee9)的配置介绍
