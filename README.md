### 如果划分时间段，说明不同的时间段，任务分工是有明确划分的。前后处理的任务性质是不一样的。
### 题目组件需要处理的事情
#### 数据处理部分
    1. 不同题目结构中， 公共统一的处理
    2. 不同结构的全局统一处理；
#### 展示部分
    1. 拆分不同结构的组件，最终汇总成一个大组件，
    2. 添加mixins， 便于大组件的重写，但是要提出约定的处理，以便于进行继承重写（ 还有待于进一步的统计和拆分）
#### 