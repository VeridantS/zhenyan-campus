# 实验3 软件架构与界面设计 V1.2

作者：沈振国，软件工程2班，24111302085。修订日期：2026年9月28日。

## 文件说明

- 同名PDF为已检查排版的阅读版；Word为可编辑版，尚未完成独立页面渲染验证。
- 同名Markdown保留完整要求和正文；content3.md是正文编辑源。
- figures含8组设计图，各有PNG与PDF；Markdown中的相对图片路径可在GitHub展示。
- build-report3.py可在本目录重建报告，并生成修正后的架构图和流程图；其余6张图复用所附图件。
- requirements.txt列生成依赖；manifest.sha256记录文件完整性（不含清单自身）。

## 网页上传

1. 打开 https://github.com/VeridantS/zhenyan-campus/tree/main/reports 。
2. 选择 Add file → Upload files。
3. 从本地 reports 文件夹把 experiment3 文件夹整体拖入网页，保留 figures 子目录；不要只上传zip。
4. 提交说明填“添加实验3架构与界面设计V1.2”，点击 Commit changes。
5. 打开刚才的提交，复制浏览器地址；这才是实验3的真实提交证据。

## 独立重建（可选，无须运行也能阅读和上传）

Windows、Python 3.12及系统黑体 C:/Windows/Fonts/simhei.ttf。
在解压后的 experiment3 目录安装 requirements.txt 依赖，再执行：

```
python build-report3.py --no-package
```

报告写回本目录，页面预览写入.preview。修改正文时先编辑content3.md。
本脚本不会访问GitHub、上传内容或读取项目密钥、数据库。
在项目原目录运行时沿用output/pdf布局；在本上传目录运行时自动使用当前目录。

## 实际状态

本地文件准备完成；远端是否提交以GitHub实际记录为准。实验2的提交编号不能作为实验3证据。
没有编码前原型记录，报告已说明三张原型属于当前设计整理；是否接受补做须由教师确认。
