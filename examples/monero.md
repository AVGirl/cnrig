# Monero mining example
Monero wallet generator: https://wallet.sumokoin.com/

## config.json
```
{
    "algo": "cryptonight",
    "background": false,
    "colors": true,
    "no-auto-update": false,
    "retries": 5,
    "retry-pause": 5,
    "donate-level": 5,
    "syslog": false,
    "log-file": null,
    "print-time": 60,
    "av": 0,
    "safe": false,
    "max-cpu-usage": 75,
    "cpu-priority": 0,
    "threads": null,
    "pools": [
        {
            "url": "pool.monero.hashvault.pro:3333",
            "user": "YOUR_MONERO_ADDRESS",
            "pass": "x",
            "keepalive": true,
            "nicehash": false,
            "variant": -1
        }
    ],
    "api": {
        "port": 0,
        "access-token": null,
        "worker-id": null
    }
}
```
## Command line
Alternatively you can use the command line.
```
./cnrig -a cryptonight -o pool.monero.hashvault.pro:3333 -u YOUR_MONERO_ADDRESS -p x
```
