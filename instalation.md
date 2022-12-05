#  Installation

## 1. Open Port
```
ufw allow 22 && ufw allow 3000
ufw enable
```

## 2. Install Screen

```
sudo apt install screen
```

## 3. Instal Node.Js 16, NPM & Git

```
sudo apt update
sudo apt upgrade
sudo apt install git
sudo apt install -y curl
```
```
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
```
```
sudo apt install -y nodejs
```

**Check Node Js version**
```
node -v
```
**Check NPM version**
```
npm -v
```
**Check Git version**
```
git --version
```

## 4 . Install Zkapp CLI

```
git clone https://github.com/o1-labs/zkapp-cli
```
```
npm instal -g zkapp-cli@0.5.3
```

**Check ZK version**
```
zk --version
```

**click YES 3x**
