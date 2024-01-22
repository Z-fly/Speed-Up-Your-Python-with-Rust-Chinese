


# Python高效编程——基于Rust语言

<a href="https://www.packtpub.com/product/speed-up-your-python-with-rust/9781801811446?utm_source=github&utm_medium=repository&utm_campaign="><img src="https://wqxuetang.oss-cn-beijing.aliyuncs.com/cover/3/243/3243404/3243404.jpg" alt="Speed Up Your Python with Rust " height="256px" align="right"></a>

这是[Python高效编程——基于Rust语言](http://www.tup.tsinghua.edu.cn/booksCenter/book_09955101.html)的存储库，由我发布。

**通过使用 PyO3 在 Rust 中创建 Python pip 模块来优化 Python 性能** 

## 这本书是关于什么的？
Rust是一门令人兴奋的新语言。它为开发人员提供了没有垃圾收集机制的内存安全，从而带来了快速的运行和低内存占用。但是，用Rust重写一切可能是昂贵和有风险的，因为Rust中可能没有对要解决的问题的包支持。这就是Python绑定和pip的用武之地。本书将使开发人员能够用Rust编写可以使用pip安装的模块，这样就能够在需要的时候注入Rust，而不需要承担重写整个系统的风险和工作量。这种方法使开发人员能够在Python项目中尝试和使用Rust。

本书涵盖了以下令人兴奋的功能：
* 探索 Python 开发人员在 Rust 中编码时需要理解的 Rust 编程语言的怪癖
* 了解多处理和线程安全的权衡编写并发代码
* 使用 Cargo 和 crate 构建和管理软件项目
* 将 Rust 代码与 Python 融合，以便 Python 可以导入和运行 Rust 代码
* 在 Docker 中部署使用私有 Rust pip 模块的 Python Flask 应用程序
* 检查并创建您自己的应用程序Rust 中的 Python 对象



如果您觉得这本书适合您，请立即获取您的[副本](http://www.tup.tsinghua.edu.cn/booksCenter/book_09955101.html)！

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a> 

## 说明和导航
所有代码都组织到文件夹中。例如，第 02 章。

代码如下所示：
```
use std::error::Error;
use std::fs::File;
use csv;
use super::structs::FootPrint;
let code = "5 + 6";
let result = py.eval(code, None, Some(&locals)).unwrap();
let number = result.extract::<i32>().unwrap();
```


**以下是本书所需的内容：**
本书适合那些希望使用 Rust 加速 Python 代码并在 Python 系统中实现 Rust 而不改变整个系统的 Python 开发人员。您将能够了解与 Rust 编程相关的所有主题。要充分利用本书，需要具备 Python 基础知识。

使用以下软件和硬件列表，您可以运行本书（第 1-11 章）中的所有代码文件。
### 软件和硬件列表
| 章节| 所需软件| 所需操作系统 | 
| -------- | ------------------------------------------------ | ----------------------------------- | 
| 1 | Python 3 | Windows, Mac OS X, and Linux (Any) |
| 1 | Rust | Windows, Mac OS X, and Linux (Any) |
| 1 | Docker | Windows, Mac OS X, and Linux (Any) |
| 1 | PYO3 | Windows, Mac OS X, and Linux (Any) |
| 1 | Redis | Windows, Mac OS X, and Linux (Any) |
| 1 | PostgreSQL | Windows, Mac OS X, and Linux (Any) |


我们还提供了一个 PDF 文件，其中包含本书中使用的屏幕截图/图表的彩色图像。[点击此处下载](https://static.packt-cdn.com/downloads/9781801811446__ColorImages.pdf)。

## 了解作者
**Maxwell Flitton**
是一名软件工程师，为开源财务损失建模基金会 OasisLMF 工作。2011年，麦克斯韦获得英国林肯大学护理学理学学士学位。在医院急症室轮班 12 小时的同时，麦克斯韦尔在英国开放大学获得了另一个物理学学位，随后又迈向了另一个里程碑，获得了伦敦大学学院医学物理和工程研究生文凭。他参与过许多项目，例如为德国政府开发医学模拟软件以及指导伦敦帝国理工学院的计算医学学生。他还拥有金融科技和 Monolith AI 方面的经验。



## 作者的其他书籍
[Rust Web 编程 ](https://www.packtpub.com/product/rust-web-programming/9781800560819?utm_source=github&utm_medium=repository&utm_campaign=) 



### 下载免费的 PDF 

 <i>如果您已经购买了本书的印刷版或 Kindle 版本，则可以免费获得无 DRM 的 PDF 版本。</i>