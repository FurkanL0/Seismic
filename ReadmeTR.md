# Seismic

![image](https://github.com/user-attachments/assets/794b1678-110c-4bf5-8514-e5d8341ce84c)

| Özellikler        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 2 |
| **RAM**          | 4 GB                     |
| **Storage**      | x GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Ucuz  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Ucuz |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Ucuz |

## Rust İndirelim

```bash
curl https://sh.rustup.rs -sSf | sh
```

- 1 

![image](https://github.com/user-attachments/assets/2a60a5a0-d5f4-4e1a-9b7e-1189d3719861)

```bash
. "$HOME/.cargo/env"
```

## Sfoundryup İndiriyoruz.

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

- İnmesi gerçekten uzun sürüyor haberiniz olsun.

## Repoyu İndirelim : 

```bash
git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git
```

```bash
cd try-devnet/packages/contract/
```


## Deploy İşlemleri : 

```bash
bash script/deploy.sh
```

- Enter.

- Faucet alıyoruz. : https://faucet-2.seismicdev.net/
- Faucetin gelmesini bekliyoruz - cüzdana geçsin 30-45 sn bekleyin.

- Enter'e bas.


## 7. Deploy İle Etkileşim : 

- Bun'u indiriyoruz.

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
```bash
bash script/transact.sh
```

- Enter.

- Faucet Alıyoruz : https://faucet-2.seismicdev.net/
- Hemen aldık diğer aşama yapma hocam bekle 30-40 sn cüzdana geçsin faucet.


### Ağ Bilgileri ; 
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
