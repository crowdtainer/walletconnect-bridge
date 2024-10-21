## Archived repository

# WalletConnect Bridge Server

Self-hosting bridge server for relaying WalletConnect connections in Crowdtainer.

Up until the time of this writting, WalletConnect (the company behind the 'walletconnect protocol') does not provide any supported open source backend implementation of their protocol - (neither v1 or v2!). What they run in their domain API's is closed source, and what used to be available as open source is no longer maintained by them.

Therefore this folder provides the needed code for self-hosting a bridge server, forked from the last version available (v1) at https://github.com/walletconnect/node-walletconnect-bridge, but with dependencies updated and any modifications needed to make the service functional.

It is important to be able to self-host all parts of an application, both for decentralization as well as cost-saving (GDPR compliance).

To build & run:
```sh
docker compose up -d --build walletconnect-bridge-server 
```
