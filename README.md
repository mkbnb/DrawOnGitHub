# DrawOnGitHub

一个可以在你的GitHub贡献墙上画画的项目
- 你需要安装git
- 更改git的全局提交者邮箱为你的邮箱
- 画好一张好看的像素画
- 运行这个程序
- 上传自动生成的仓库到GitHub
- 大功告成

要是不想要了把GitHub上的项目删了像素画就会消失

## 像素画要求

将图像命名为 `img.png` 放置到 `main.py` 文件的旁边

图像将被量化到五种颜色, 程序内有预览

图像要求:
- 灰度图像（仅读取图像的 R 值）
- 高度为 7, 宽度随意（只要显示得下）
- 命名为 `img.png`

## 开始时间

意思是你想要画像素画的区域的最左上角的那一天

向右绘制, 确保右边一块是空的

## 运行项目

执行以下命令以运行 `main.py` 文件：

```bash
python main.py