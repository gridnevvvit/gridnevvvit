I'm the member of the [YDB](https://ydb.tech) team which is an open-source Distributed SQL database that combines high availability and scalability. My
responsibilities include specification generation, active development, bug fixing and the maintenance of the several projects in the YDB team

Previously I was core upstream contributor for the OpenStack Data processing service (Sahara), which provides big data cluster
management and elastic data processing in OpenStack.

Stack: C++, Python, gRPC, Protobuf, AsyncIO, Jaeger, SQLAlachemy, YDB, OpenStack

Impact:

- Implemented the YDB Python SDK in order to provide an ability to use the YDB in applications. This includes implementing the transport layers using gRPC and protocol buffers, client side balancing algorithms and client adapters such as SQLAlchemy.
- Implemented the major part of the YDB test and maintenance infrastructure, including stress testing, test pipelines, chaos testing for the YDB.
- Developed the Managed YDB as a Service product in the Yandex Cloud.
- Developed the Query Replay feature which is a pipeline that collects queries data from production clusters and processes these queries to avoid regressions in the YDB Query Engine.
- Developed several components to distribute the load evenly across the YDB servers.
- Developed and refactored several components in YDB to improve performance of Query Processing engine.
- Developed sequences support in YDB
- Built the platform to support stored columns in YDB.
