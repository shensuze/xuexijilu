学习记录

日期11.5

1、验证集loss上升，val也上升，因为最后的训练结果趋向于2分类的两个0、1端点，loss会开始上升。原因是过拟合或者训练验证数据分布不一致导致，即在训练后期，预测的结果趋向于极端，使少数预测错的样本主导了loss，但同时少数样本不影响整体的验证acc情况
https://www.zhihu.com/question/318399418
1
安装网上下载的whl文件
pip3 install D:\soft\py\dlib-19.8.1-cp36-cp36m-win_amd64.whl


在pycharm命令行pip的东西会安装在此文件所用的虚拟环境中
