# Round 1 介绍
# Round 1 介绍
第一步：搭建环境，包括Hadoop环境，Spark环境等。
                1.下载好Hadoop2.6.5安装包，并解压安装。
                2.配置好java环境、Hadoop环境、JDK环境。
                3.启动Hadoop，安装好HDFS。
第二步：读取日志，将日志文件传入到HDFS下。
第三步：编写程序。
                1.用mapreduce处理，将访问的ip作为value，有一个相同的ip，key就加1，就会统计出UV。
                2.将map中输出的key作为reduce中输入的value，map中输出的value作为reduce中输入的key，在reduce中进行排序，然后查看前十的ip。
                3
