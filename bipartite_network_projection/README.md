### 二分网络转单顶点网络

基本处理：使用Python下的网络分析专用模块**networkx**，完成数据的文件读取、数据处理和文件输出。

准备材料：待处理的二分网络边列表(.csv file)，包含两列信息。以academic/discipline二分网为例，则分别储存学者/系别信息，每行是学者与系别的对应关系（学科归属）。

用法：
1. 在当前文件夹下，准备Python脚本和二分网络边列表，即 bipartite_network.py 和 edgelsit.csv。

2. 打开Terminal，进入到当前文件夹路径下，键入：python bipartite_network.py，执行bipartite_network文件，按照提示输入边列表文件名，本案例中输入edgelist.csv。

3. 得到"Finished!"反馈信息后，程序完成二分网络到单节点网络的转换，并在当前文件夹下生成四个文件，分别是两个网络的nodelist和edgelist。

注意：以上文件基于Python2.7版本