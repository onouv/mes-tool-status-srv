# mes-tool-status-srv
A microservice to process tool status events

ToolStarted --> post UT increment to UT value topic

ToolStopped(Reason) --> post DT increment to DT value topic

## Fit Into Overall Architecture
![Overall Architecture](mes-deploy.png)

* ![mes-tool-mock-srv](https://github.com/onouv/mes-tool-mock-srv)
* ![mes-tool-product-srv](https://github.com/onouv/mes-tool-product-srv)
* ![mes-tool-kpi-srv](https://github.com/onouv/mes-tool-kpi-srv)
* ![mes-tool-dashboard-srv](https://github.com/onouv/mes-tool-dashboard-srv)
