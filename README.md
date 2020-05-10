# bitcoinsv-docker-compose

Pruned Bitcoin SV Listener with CLI

1.Create `.env` file on repo dir

```
BITCOIN_RPC_USER=changeme
BITCOIN_RPC_PASSWORD=changeme
```

2.Adjust `bitcoin.conf`

3.Start the listener

```
sudo docker-compose up -d
```

4.Query the RPC e.g.
```
sudo docker-compose run --rm bitcoin-cli getinfo
```
