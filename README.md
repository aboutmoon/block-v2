# block-v2

区块相关：
1. 定义一个工作量证明的结构ProofOfWork
    - a. block
    - b. 目标值
2. 提供一个创建POW的方法
    - NewProofOfWork(参数)
3. 提供一个计算哈希值的方法
    - Run()
4. 提供一个校验函数
    - IsValid()    