tensorflow 目录
===

# 第一层

- tensorflow tensorflow 实现
- third_party 第三方依赖库
- tools 工具

目录下文件是各类的脚本文件和信息文件，用于编译的事bazel的脚本文件，
BUILD和WORKSPACE

# tensorflow目录

- api_def
- common_runtime: 公共运行库，包含session, executor, threadpool, rendezvous, memory管理, 设备分配算法等。
- data
- debug
- distributed_runtime: 分布式执行模块，如rpc session, rpc master, rpc worker, graph manager。
- example
- framework: 包含基础功能模块，如log, memory, tensor
- graph: 计算流图相关操作，如construct, partition, optimize, execute等
- grappler
- kernels: 核心Op，如matmul, conv2d, argmax, batch_norm等
- lib: 公共基础库，如gif、gtl(google模板库)、hash、histogram等。
- nccl
- ops: 基本ops运算，ops梯度运算，io相关的ops，控制流和数据流操作
- platform: OS系统相关接口文件，如file system, env等。
- profiler
- protobuf: 均为.proto文件，用于数据传输时的结构序列化.
- public: API接口头文件目录，用于外部接口调用的API定义，主要是session.h。
- summary
- tpu
- user_ops
- util

