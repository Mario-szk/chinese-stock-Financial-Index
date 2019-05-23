# chinese-stock-Financial-Index
计算中国A股所有股票的3年平均财务指标,并可以按照3年平均市盈率和最近5年ROE过滤股票

使用前提:
1. 安装python3.6或者更高版本
1. 在当前目录创建python虚拟环境，运行命令 pyvenv venv
2. 安装依赖库，在当前目录打开命令行，输入 pip install -r requirement。


使用方法
1. 解压'finance2018.7z'文件到当前文件夹，解压后为finance2018文件夹，包含所有a股公司到2018年的财务数据
2. 运行calcu_3year_average_pe.py 通过3年平均收益率筛选股票，默认为市盈率范围为2-20，可以修改。
生成类似 '2018-06-09-3年平均市盈率在2和20之间的公司.xlsx'文件名的文件，里面包含筛选出来的公司。
直接用excel打开即可查看