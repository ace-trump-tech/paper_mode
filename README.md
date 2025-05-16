## 使用教程

### 一、安装与导入

#### 在线使用（推荐）

##### 克隆项目

  * 打开终端，输入以下命令将项目克隆到本地：

`git clone https://github.com/ace-trump-tech/math-modeling-template.git`

##### 导入 Overleaf

  * 登录你的 Overleaf 账号，创建一个新项目。
  * 点击 “从 GitHub 导入”，输入项目仓库地址 `[math-modeling-template](https://github.com/ace-trump-tech/math-modeling-template)`，点击 “导入”，即可将模板导入到 Overleaf 环境中。

#### 直接下载

  * 点击 [这里](https://github.com/ace-trump-tech/math-modeling-template/archive/refs/heads/main.zip)，下载模板的压缩包。
  * 解压后，将文件上传至 Overleaf 项目中。

### 二、开始编辑

##### 编辑论文内容

  * 在 Overleaf 中，点击左侧的文件列表，选择相应的.tex 文件进行编辑。
  * 摘要部分编辑 `abstract.tex`，模型建立与求解部分编辑 `model.tex`，结果分析部分编辑 `result.tex`，结论部分编辑 `conclusion.tex` 等。

##### 插入数学公式

  * 在编辑器中，使用 `\[公式\]` 或 `\begin{equation}公式\end{equation}` 来插入数学公式。

##### 添加图表

  * 在 Overleaf 中，点击 “上传” 按钮，选择要添加的图片文件。
  * 在.tex 文件中，使用 `\includegraphics{图片文件名}` 来插入图片，并使用 `\caption{图表标题}` 来添加图表标题。

### 三、编译查看效果

  * Overleaf 提供实时预览功能，当你完成一部分内容的编辑后，点击右上角的 “重新编译” 按钮，即可在右侧的预览窗口中查看论文的实时渲染效果。

### 四、导出论文

  * 编辑完成后，点击 Overleaf 右上角的 “菜单” 按钮，选择 “下载 PDF”，即可导出论文的 PDF 文件。

## 常见问题

#### 如何调整论文格式？

  * 在主.tex 文件中找到相应的设置部分，根据 Overleaf 的 Latex 语法进行修改。

#### 如何添加引用？

  * 在论文中引用参考文献时，将参考文献信息添加到 `references.bib` 文件中，然后在需要引用的文本位置使用 `\cite{引用标签}` 命令进行引用。

## 联系我们

如果你在使用模板过程中有任何疑问，或者需要进一步的帮助，可以通过以下方式联系我们：

  * **GitHub 项目页面** ：[math-modeling-template](https://github.com/ace-trump-tech/math-modeling-template)
  * **电子邮箱** ：[your-email@example.com]
