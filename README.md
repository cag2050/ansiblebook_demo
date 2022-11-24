

#### 开发步骤
1. 创建项目时选择创建虚拟环境，或者：进入项目的根目录，创建虚拟环境： ```virtualenv --python=python2 venv```
2. 进入虚拟环境：```source venv/bin/activate```
3. 安装软件包后，写入文件：```pip freeze > requirements.txt```
4. 根据文件安装依赖：```pip install -r requirements.txt```

说明：
1. vagrant 版本：2.2.19

vagrant 命令 | 说明
--- | ---
vagrant version | 查看版本
vagrant | 帮助信息
vagrant COMMAND -h | 单个COMMAND的帮助信息

参考资料 | 说明
--- | ---
书籍《奔跑吧Ansible（第2版）：探索自动化配置与部署捷径》| https://book.douban.com/subject/30370645/
书籍《奔跑吧Ansible（第2版）：探索自动化配置与部署捷径》，代码仓库 | https://github.com/ansiblebook/ansiblebook ，分支：2nd-edition