# Install-miniconda
## 1. 安装
wget -c https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
## 2. 更改文件权限并执行
chmod 777 Miniconda3-latest-Linux-x86_64.sh </br>
sh Miniconda3-latest-Linux-x86_64.sh
## 3. 添加环境变量
export PATH=<miniconda_dir>/bin:$PATH
## 4. 使其生效
source ~/.bashrc
## 5. 启用bash的conda activate
conda init bash
## 6. 重启终端

