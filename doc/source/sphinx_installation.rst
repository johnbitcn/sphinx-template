

Sphinx 安装和配置
======================


Sphinx 安装
----------------------

.. code-block:: powershell

    pip install sphinx
    pip install sphinx-autobuild
    pip install sphinx-rtd-theme


安装外部插件
----------------------

| graphviz
| MiKTex


配置 Sphinx 
----------------------

Make files
----------------------

生成各种文档

:HTML:
    | 生成HTML文档
    | :code:`make.bat html`

:LaTex:
    | 生成LaTex PDF 文档
    | 先生成 LaTex 文档 
    | :code:`make.bat latex`
    | 再将 tex 文件生成 PDF 
    | :code:`cd .\\build\\latex\\`
    | 这一步要生成两次 :code:`xelatex test.tex`
