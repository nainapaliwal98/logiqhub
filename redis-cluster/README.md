# Redis cluster monitoring

## Features
* Monitor one or more redis clusters via LOGIQ prometheus connector
* Dropdown selector to switch redis running on different namespaces

## Configuration

* Edit redis-cluster-monitoring.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to redis and redis-2

## Steps to import

* Download redis-cluster-monitoring.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f redis-cluster-monitoring.json
```

## Screenshot
![image info](./redis-dash-0.png)
![image info](./redis-dash-1.png)
