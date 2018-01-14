#python3
1. [Annoconda3,5](https://repo.continuum.io/archive/Anaconda3-4.2.0-MacOSX-x86_64.sh)
```
bash *.sh -p <prefix> -b
```
2. install requirements
```
<prefix>/anaconda3/bin/pip  install -i https://pypi.douban.com/simple -r requirements
```
3. 关于virtual-env的使用 
    TODO 存在问题
    * 参考[virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html)
    ```

    export PYTHON_BIN_HOME=/Users/devuser/Local/mypython/pythonenv
    export WORKON_HOME=$PYTHON_BIN_HOME/.virtualenvs
    export PROJECT_HOME=$PYTHON_BIN_HOME/Devel
    source /Users/devuser/Local/mypython/pythonenv/anaconda3/bin/virtualenvwrapper.sh
    ```
    * 设置alias python3="...."完成python3.5的设置

#pycharm professional
参考[网站](http://idea.lanyus.com/)

# python 包的问题解决网站
参考[网站](https://www.lfd.uci.edu/~gohlke/pythonlibs/)
