# RabbitMQ Performance Testing Tool

Modification of PerfTest tool from RabbitMQ that allows us to created more than one channel per producer/consumer connection.

```
 -W,--chConsumers <arg>     channel count Per consumer connection
 -w,--chProducers <arg>     channel count Per producer connection
```

There are no changes to how the options `R` and `r`. The semantics are the same. `r` is the producing rate of a single connection regardless whether it has 1 channel or N channels. Same for 'R'.
