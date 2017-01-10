# snoop
An centralised configuration service for multiple project


Why have this project?  lots of projects need configuration (Properties resource in Java) system to support configurable, it means that the behavior of the project is configurable, and at some times we need this configuration can be hot changed without restart the service.

snoop-parent - An maven aggregator pom project
snoop-http - An light weight http server base on Netty.
snoop-server - Core server of this configuration service.
snoop-web - An web management system.
snoop-client - An Java Client wrapper.
