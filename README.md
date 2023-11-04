# -linux-
本系统采用C++技术栈，并结合 Docker、gRPC、Protocol Buffers等工具和框架的分布式Linux性能分析监控系统。通过模块化的设计，该项目旨在实现对分布式Linux 系统的性能监控和分析。
应用技术： C++、Docker、gRPC、protobuf、Cmake、工厂方法。                
项目描述：本系统采用C++技术栈，并结合 Docker、gRPC、Protocol Buffers等工具和框架的分布式Linux性能分析监控系统。通过模块化的设计，该项目旨在实现对分布式Linux 系统的性能监控和分析。
主要工作：1、构建Docker模块：构建一个容器，包含CMake、gRPC、Protocol Buffers等多个依赖，以便在多台服务器上部署环境。
2、构建Monitor模块：实现灵活的监控接口，能够有效地捕获CPU状态、系统负载、软中断、内存、网络等性能指标，同时还需要模拟真实性能问题。
3、调用gRPC框架：构建Server和Client，实现模块之间的远程连接，同时降低模块间的耦合性。
4、Protocol Buffers序列化：构建整个项目的数据结构，并确保高效的数据交换。
