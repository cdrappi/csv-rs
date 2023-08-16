# csv-rs

csv-rs crate库提供了对HYGON CSV API接口的rust实现。

CSV API根据其被调用的方式分为：
1. 在主机侧调用的Management API
2. 在虚拟机侧调用的Guest API。

其中Management API根据其功能又分为：
1. 管理CSV Platform的API
2. 启动CSV虚拟机的API

该crate中会陆续实现上述API的high level接口，提供给
上层软件调用。

## Management API
### Platform Management
To be added in the future.
### Launch Management
To be added in the future.
## Guest API
请参考[Guest API 相关文档](docs/guest/README.md).