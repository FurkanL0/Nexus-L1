# Nexus L1 Node Kurulum

![image](https://github.com/user-attachments/assets/ca6aff98-5366-4775-8d69-7334fc390765)

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Ucuz  |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Ucuz |

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 10++ GB                     |
| **Disk**      | 50 GB SDD                   |
| **Internet Hızı**      | 100 Mbps |
| **İşletim Sistemi**      | Ubuntu 24 |

- Anlık Kullanım : 

![image](https://github.com/user-attachments/assets/1baab409-3ea2-4985-8259-d57fdb5c5916)


# Kayıt : 

-  https://app.nexus.xyz/ - Register on the site with your wallet and email at the top right - it's better to use the same one you used on the old testnet.

## 1. Server Güncelleme : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Paketleri İndirip Güncelleme:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file nano btop unzip lz4 -y
```

```bash
sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler -y
```

## Rust Indirme : 

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

![image](https://github.com/user-attachments/assets/0efae43c-b5ba-488c-9f3e-de0aa12698f4)

- 1 Seçelim sonra enter.

```bash
source $HOME/.cargo/env
```

![image](https://github.com/user-attachments/assets/3e5d7403-25cf-46db-b2d5-d521508e8617)


```bash
rustup target add riscv32i-unknown-none-elf
```

![image](https://github.com/user-attachments/assets/cb08651c-6db6-4106-a5e0-285cb399d960)


# 3. Nexus CLI : 

```bash
screen -S nexus
```

```bash
curl https://cli.nexus.xyz/ | sh
```
- Soruya Y yazıp enterleyin.

```bash
source ~/.bashrc
```

![image](https://github.com/user-attachments/assets/edc927f7-d6a6-45de-b610-49dcc8af1571)


## Başlatalım : 

- Siteden Node ID Alalım.
- Link : https://app.nexus.xyz/nodes

![image](https://github.com/user-attachments/assets/5bbc7e54-3c93-4699-a222-15bd175d76a7)


```bash
nexus-network start --node-id your-node-id
```

- "your-node-id" kısmına siteden aldığınız nodeID'niz ile değiştirip başlatın.

![image](https://github.com/user-attachments/assets/b734e345-e6d2-46bf-97d8-91b81d4f8cd5)

- Kurulum Öncesi Deneme Olduğu İçin Error'lu ; 

![image](https://github.com/user-attachments/assets/5a2d713d-cbeb-41d1-b2ae-6af40dcd5f18)



- CTRL'ye basılı tutup A ve D yaparak Screenden çıkabilirsiniz.


## Web : 

![kass](https://github.com/user-attachments/assets/579f806b-9a21-4902-85f9-23aadea7b8b6)


## Link : https://app.nexus.xyz/


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
