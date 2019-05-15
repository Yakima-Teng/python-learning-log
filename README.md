# python-learning-log

一个python3学习案例（实际使用python版本为：3.7.3）。

## 创建虚拟环境

进入项目根目录，执行以下命令（这里运行了模块venv，并用它创建了一个名为11_env的虚拟环境）。

```bash
python -m venv 11_env
```

## 激活虚拟环境

执行以下命令：

```bash
source 11_env/bin/activate
```

这个命令会激活环境。当环境处于激活状态时，你可以在环境中安装包，并使用 已经安装的包。你在11_env中安装的包仅在该环境出于活动状态时才可用。

要停止使用虚拟环境，可执行下述命令：

```bash
deactivate
```

如果关闭运行虚拟环境的终端，虚拟环境也将不再出于活动状态。

## 安装Django

```bash
pip install Django
```

这里我们装的是最新的Django 2.2.1版本，可通过下面的方式查看版本号：

```python
import django
print(django.get_version())
```
