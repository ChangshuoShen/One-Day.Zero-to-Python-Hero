# Zero to Python Hero in One Day

欢迎来到 **Python 教程与实用技巧** REPO！本项目旨在为学习者提供 Python 编程的基础知识和常用技巧，涵盖从基础语法到经典数据分析工具的使用。每个章节都以 Jupyter Notebook 的形式提供，便于学习、实践和复现。

---

## 项目结构

以下是项目的主要目录和文件说明：

- **[py_intro.md](py_intro.md)**  
  Python 基础知识与技巧的详细介绍，包括 Python 的特点、优势、版本信息，以及高效编程技巧等内容。

- **Jupyter Notebook 文件**  
  每个章节的内容都以 `.ipynb` 文件形式提供，具体如下：
  
  1. **[Python 编程入门](01_python_basics.ipynb)**  
      - Python 的基本语法和特性。
  2. **[程序流程控制](02_control_flow.ipynb)**  
      - 条件判断、循环结构及流程控制。
  3. **[内置数据类型](03_builtin_data_types.ipynb)**  
      - Python 的基本数据类型，如 `int`、`float`、`str` 等。
  4. **[复合数据类型](04_composite_data.ipynb)**  
      - 列表、元组、字典、集合等复合数据结构的用法。
  5. **[函数](05_functions.ipynb)**  
      - 函数的定义与调用、参数传递及高阶函数。
  6. **[类与对象](06_classes_and_objects.ipynb)**  
      - 面向对象编程，包括类的定义、继承与多态。
  7. **[Numpy 基础](07_numpy_basics.ipynb)**  
      - 使用 Numpy 进行数组操作和科学计算。
  8. **[Pandas 基础](08_pandas_basics.ipynb)**  
      - 数据分析工具 Pandas 的基本使用方法。

- **其他目录**：
  - **[data/](data/)**：存储项目中使用的示例数据文件。
  - **[imgs/](imgs/)**：存储项目中使用的图片资源。

---

## 如何使用

1. **克隆项目**：
```bash
git clone git@github.com:ChangshuoShen/One-Day.Zero-to-Python-Hero.git
cd One-Day.Zero-to-Python-Hero
```


2. **安装依赖**
```bash
conda create -n python-hero python=3.10 -y
conda activate python-hero
pip install -r requirements.txt
```


3. **运行Jupyter Notebook**
```bash
jupyter notebook
```

之后在浏览器中打开对应的`.ipynb`文件开始学习


## 推荐学习路径
1. 从[[py_intro.md](./py_intro.md)]开始，了解python的基础知识和编程技巧
2. 依次阅读每个章节的`.ipynb`文件，运行代码并手动实践
3. 使用官方文档和其他资源，深入学习相关主题