# LOADVIEW
 一个简单的公共类加载视图
注意：gif 图通过 Add Files to "xxx"【工程名称】添加，否则可能出现找不到源文件的情况
网络加载完成移除 [loadingView removeFromSuperview];
视图加载失败 没网的时候  [weakSelf noNetWork];
数据加载失败 有网的时候  [weakSelf dataError];
数据加载记载成功 [weakSelf delayMethod];
