## spark-kafka-0-8
---------------------
> - 支持动态调节 streaming 的 批次间隔时间 （不同于sparkstreaming 的 定长的批次间隔，StructuredStreaming中使用trigger实现了。） <br/>
> - 支持在streaming过程中 重设 topics，用于生产中动态地增加删减数据源 <br/>
> - 添加了速率控制，KafkaRateController。用来控制读取速率，由于不是用的sparkstreaming，所有速率控制的一些参数拿不到，得自己去计算。
> - 提供spark-streaming-kafka-0-10_2.10 spark 1.6 来支持 kafka的ssl <br/>
> - 支持rdd.updateOffset 来管理偏移量。 <br/>
--------------------

 ## spark-streaming-kafka-0-10
 * 只是结合了 sparkstreaming 1.6 和 kafka 010 。 使低版本的spark能够使用kafka的ssl验证 <br>
 --------------------
 > * 支持 SSL
 > * 支持spark 1.6 和 kafka 0.10 的结合
 > * 支持管理offset
 --------------------
