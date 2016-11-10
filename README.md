泰坦尼克号生还者分析
====================

# Python requirement

## 安装 conda 包管理器

### Python 2
    wget https://repo.continuum.io/miniconda/Miniconda2-latest-Linux-x86_64.sh
    bash Miniconda2-latest-Linux-x86_64.sh
    conda list

## 建立并激活虚拟环境
    conda create -n py2env python=2
    # 激活虚拟环境
    source activate py2env
    # 退出虚拟环境
    source deactivate
    
## 安装虚拟环境    
    conda install -n py2env pandas
    conda install -n py2env numpy
    conda install -n py2env matplotlib
    conda install -n py2env jupyter
    conda install -n py2env scikit-learn


