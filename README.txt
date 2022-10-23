# 打包
pyinstaller -F main.py -i resources/hundsun.ico -n SQLExecuteTool -w

# 打包清理
sh pyinstaller_clean.sh 

# 升级记录
20221023 增加打印文件路径，方便脚本执行错误定位和后续补充执行
20220502 修复执行路径中含有空格执行报错的问题
20211224 初始化项目V1.0