# Seismic

![image](https://github.com/user-attachments/assets/794b1678-110c-4bf5-8514-e5d8341ce84c)

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 2 |
| **RAM**          | 8 GB                     |
| **Storage**      | 256 GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |


## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## Rust

```bash
curl https://sh.rustup.rs -sSf | sh
```

- 1 

![image](https://github.com/user-attachments/assets/2a60a5a0-d5f4-4e1a-9b7e-1189d3719861)

```bash
. "$HOME/.cargo/env"
```

## Install Sfoundryup

```bash
curl -L \
     -H "Accept: application/vnd.github.v3.raw" \
     "https://api.github.com/repos/SeismicSystems/seismic-foundry/contents/sfoundryup/install?ref=seismic" | bash
```

![image](https://github.com/user-attachments/assets/dbcb936d-392a-4a3a-b019-e351e5aad7ce)


```bash
source /root/.bashrc
```

```bash
sfoundryup
```

![image](https://github.com/user-attachments/assets/ee61d6e6-2732-46da-b5cf-a85891e597fc)

- Wait download. 

## Install Repo : 

```bash
git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git
```

![image](https://github.com/user-attachments/assets/9d4e954c-4833-49c0-8fbf-6b1272990f99)


```bash
cd try-devnet/packages/contract/
```


## Deploy : 
```bash
bash script/deploy.sh
```
![image](https://github.com/user-attachments/assets/620a8036-3fb4-4f47-85c2-888875bd035b)


- Enter.

![image](https://github.com/user-attachments/assets/95600ebd-7114-4f89-af04-cbc9244f1beb)


- Claim Faucet : https://faucet-2.seismicdev.net/

![image](https://github.com/user-attachments/assets/c238e433-0216-4a44-aaeb-66a265145953)


- Wait for faucet - 30-45 second.
- Enter.

![image](https://github.com/user-attachments/assets/41fc1a6a-364e-48cd-9c0c-b58f9f5eadd0)

- Nice

## 7. Intract With Deploy : 

- Install bun.

```bash
cd
curl -fsSL https://bun.sh/install | bash
```

```bash
source /root/.bashrc
```

- Run ; 

```bash
cd try-devnet/packages/cli/
bun install
```
![image](https://github.com/user-attachments/assets/25751690-c254-49a2-ab7f-e75caa0d2e59)


```bash
bash script/transact.sh
```
![image](https://github.com/user-attachments/assets/ede8fd0e-29c2-4942-bbbf-9211087c6557)


- Enter.

- Faucet : https://faucet-2.seismicdev.net/
![image](https://github.com/user-attachments/assets/66d0a4c9-b889-4c08-8f8d-789f2674e24f)

- Wait for faucet - 30-45 second.


### Chain İnfo ; 
```bash
Network Name: Seismic devnet

Currency Symbol: ETH

Chain ID: 5124

RPC URL (HTTP): https://node-2.seismicdev.net/rpc

RPC URL (WebSocket): wss://node-2.seismicdev.net/ws

Explorer: https://explorer-2.seismicdev.net

Faucet: https://faucet-2.seismicdev.net

Starter Repo: https://github.com/SeismicSystems/seismic-starter
```
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
