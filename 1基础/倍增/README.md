### 倍增
- 常见解决问题RMQ和LCA
- 解决一个需要大量模拟的问题，把问题预处理成部分子问题
  - 比如如何用最少的砝码称重[0,31]之间的所有重量
    - 只需要使用1，2，4，8，16即可
  - 同理，如果需要处理[0,1023]之间的所有情况
    - 只需要9个砝码
  - 比如处理量m<=10^18，只需要预处理65以内的情况即可