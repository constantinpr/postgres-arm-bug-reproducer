# postgres-arm-bug-reproducer

Update these values in parameters.json
```
 "administratorLoginPassword": {
      "value": "your-password"
    },
    "serverName": {
      "value": "your-server-name"
    },
```

```
az group deployment create --name postgres-debug -g postgres-debug --template-file postgresql.json --parameters parameters.json
```
