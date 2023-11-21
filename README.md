# Install-miniconda
## 1. 安装
wget -c https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
## 2. 更改文件权限并执行
chmod 777 Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh
## 3. 添加环境变量
export PATH=/bin:/usr/bin:$PATH
## 4. 使其生效
source ~/.bashrc

