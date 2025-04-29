# 并行第二次作业
这些是我实现密文猜测任务并行化所用到的代码文件，
其中md5_neon.h与md5_neon2.cpp是实现arm架构并行化密文猜测的散列函数，
main.cpp和correctness调用了并行化的散列函数进行计算，
我使用main.py对实验所给的长字符串拆成4段。
