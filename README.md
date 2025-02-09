# README_about_the_basic_environment

## 1.你可以直接使用Anaconda导入yaml文件

## 2.手动配置（自行配置conda吧）

### （1）配置cuda和cudnn：

==（注意：由于地区原因，nvidia官网可能需要科学上网，请自行解决）==

[【保姆级教程】Windows安装CUDA及cuDNN_windows安装cudnn-CSDN博客](https://blog.csdn.net/qq_40968179/article/details/128996692?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0-128996692-blog-137825313.235^v43^pc_blog_bottom_relevance_base1&spm=1001.2101.3001.4242.1&utm_relevant_index=3)

[CUDA与CUDNN在Windows下的安装与配置（超级详细版）_windows安装cudnn-CSDN博客](https://blog.csdn.net/YYDS_WV/article/details/137825313)

[windows安装cuda与cudnn_windows cudnn-CSDN博客](https://blog.csdn.net/qq_58158950/article/details/142991177?ops_request_misc=&request_id=&biz_id=102&utm_term=windows安装cudnn&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-2-142991177.nonecase&spm=1018.2226.3001.4187)

你可以参考更多，这里只是一些例子，由个人具体的显卡驱动版本号和具体系统环境而定

### （2）Pytorch官网：

[PyTorch - PyTorch 深度学习库](https://pytorch.ac.cn/)

[PyTorch](https://pytorch.org/)

#### **下载地址（请根据自身cuda版本来，注意：2.4.0不要下载！！！！！！）**：

[Previous PyTorch Versions | PyTorch](https://pytorch.org/get-started/previous-versions/)

[之前的 PyTorch 版本 | PyTorch - PyTorch 深度学习库](https://pytorch.ac.cn/get-started/previous-versions/)

### （3）conda相关指令以及常用cuda指令：

[Conda 常用命令大全（非常详细）零基础入门到精通，收藏这一篇就够了_conda命令大全-CSDN博客](https://blog.csdn.net/jasonOI/article/details/144468484)

```
nvidia-smi
#查看显卡状态，包括cuda版本，驱动版本，显存占用等
nvcc --version
#检查cuda相关组件安装版本
```

### （4）一些不能直接pip或者conda安装的包：

apex（详见网络相关资料，已经clone在根目录）

依赖项目：ViT-pytorch有requirements.txt需要使用pip指令批量安装

