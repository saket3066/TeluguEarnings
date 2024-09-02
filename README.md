# TeluguEarnings

**Use Command One By One:**
```
sudo apt update && sudo apt install curl && curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh

```
```
sudo docker pull nillion/retailtoken-accuser:latest

```

```

mkdir -p nillion/accuser && sudo docker run -v ./nillion/accuser:/var/tmp nillion/retailtoken-accuser:latest initialise

```

**Save your Private Key**
```
cat ~/nillion/accuser/credentials.json
```

**Final Command To Run**
```
--- Copy from Website ---

