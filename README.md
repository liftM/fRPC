# fRPC

![](https://img.shields.io/badge/stability-experimental-red)

fRPC is a mod that adds RPC capabilities to Factorio. It provides two new buildings that interact with the circuit network:

- _Sensors_ read values from the circuit network and expose them as metrics on the fRPC HTTP server.
- _Receivers_ broadcast values onto the circuit network from inputs provided to routes on the fRPC HTTP server.

```
sudo docker build -t frpc-factorio:0.0.1 .
```
