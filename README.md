# LegalHelper
####################版本说明####################

Windows系统可以稳定运行的最新版本为3.95

Mac系统可以稳定运行的最新版本为4.01

####################法典小助手Q&A####################

Q：法典小助手是做什么的？

A：法典小助手是一个检索法条内容的小程序。

Q：如何安装法典小助手？

A：第1步，您需要在您的电脑上安装Python。它的官网是：https://www.python.org/
。在“downloads“下拉菜单中选择您的操作系统进入下载页面。在下载页面，使用Windows的用户，请点击蓝色的Windows installer(64-bit)。使用macOS的用户，请点击蓝色的macOS 64-bit universal2 installer。下载完成后进行安装。国内连接Python的速度比较慢，请耐心等待。

  第2步，您需要安装法典小助手依赖的库，包括python-docx库和pyperclip库。
  
  使用Windows的用户，请同时按下windows键和r键，在弹出的“运行”窗口中输入cmd，按回车，在弹出的黑框中执行以下操作：
  复制“pip install -i https://pypi.tuna.tsinghua.edu.cn/simple python-docx”（不要带引号），并按回车，等待下载结束。
  复制“pip install pyperclip”（不要带引号），并按回车，等待下载结束。
  一般来说，下载读条结束后出现白色、黄色字样，代表下载成功。出现红色字样，则代表您的网络有问题，您可以用手机给电脑开热点，或者你懂的:）。
  
  使用macOS的用户，打开终端（terminal），执行以下操作：
  复制“pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple python-docx”（不要带引号），并按回车，等待下载结束。
  复制“pip3 install pyperclip”（不要带引号），并按回车，等待下载结束。

  第3步，请从网页中下载“法典小助手.zip”并解压。至此，法典小助手安装完毕。

Q：如何使用法典小助手？

A：第1步，解压后会得到“法典小助手”文件夹，打开它，您会看到一个名为法典小助手3.6.py的文件，和一个“法律”文件夹。

  第2步，打开“法律”文件夹，现在是空无一物的。您可按照自己的需求，新建一些文件夹并以法律门类命名（例如命名为商法）。法典小助手将按照您创建的文件夹分门别类地排列显示法条文件。

  第3步，从北大法宝或国家法律法规数据库中下载docx格式的法条文件（不能是doc格式。doc格式的文件可以打开后按F12，另存为docx格式），放入您自己新建的文件夹中。请注意：不能将法条文件直接放置在“法律”文件夹下。请注意：法典小助手过去、现在、将来均不会提供爬虫功能，您需要自行下载法律文件。原因有三：第一，爬虫存在巨大的法律风险。第二，爬取公用网站的行为是令人厌恶的。第三，法典小助手只是一个法学生的业余作品，开发者本人完全没有开发爬虫的能力。

  第4步，回到“法典小助手”文件夹，打开.py后缀的文件，尽情享受法典小助手吧！

Q：法典小助手有哪些功能？

A：它有很多功能，容我一一道来。

  检索功能：在窗口左上角您可以看到输入框，输入您需要检索的内容，并在下方的检索范围框选中需要检索的法条，按回车检索，匹配到的关键词将以高亮显示。

  多选功能：在窗口左侧，您会看到检索范围框，用鼠标单击您需要检索的法条。

  清除功能：按下delete键即可清除右侧窗口的检索内容。

  清除并检索功能：需要清空之前的内容并进行新一次检索？同时按下shift和回车就可以了。

  多关键词检索功能：您可在输入框中输入多个关键词，用空格隔开，按回车检索。每个关键词将用不同颜色高亮显示。

  条文号检索功能：想查找民法典第一千一百六十五条吗？只用输入1165就可以了。或许您在找刑法第一百六十九条之一？输入169.1试试吧。

  复制功能：您需要把查找到的内容复制到笔记中吗？同时按下ctrl键和s键（macOS还可以同时按下command键和s键），这些内容将复制到剪贴板。

  范围输出功能：用“-”号连接两个数字，即可输出该范围内的法条。

  分屏功能：有时您需要一边记笔记一边查法条。windows下同时按下windows键和左键、右键、上键即可左分屏、右分屏、全屏，同时按windows键和下键即可恢复原状。macOS尚不支持此操作。

Q：法典小助手的更新分哪几种？

A：分两种。第一种是功能更新，第二种是漏洞补丁。

Q：法典小助手有病毒吗？会危害我的计算机安全吗？

A：法典小助手是基于GNU GPLv3的自由软件，“法典小助手3.6.py”是它的源代码，您可自行查验有无病毒。根据法律的一般原则和GNU GPLv3关于演绎部分、程序接口部分的规定，法典小助手的开发者对Python、python-docx库、pyperclip库的安全性不承担任何责任，亦对任何主体基于法典小助手创作的演绎作品不承担任何责任。

Q：我使用法典小助手有法律风险吗？

A：法典小助手是适用GNU GPLv3的自由软件。根据您的使用目的不同，法律风险有所不同。

  如果您是个人使用者，就您的用途而言，没有任何法律风险。您可以自由地使用它、研究它、向您的朋友分发它。

  如果您基于法典小助手开发您的软件（无论它们是善意的还是恶意的、有偿的还是无偿的），您需要注意以下两点：第一，根据GNU GPLv3的传染性规定，您创作的部分也是自由软件。第二，您需对您创作的部分负完全的责任。


  
  
  




  
  
