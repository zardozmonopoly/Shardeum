<h1 align="center">Shardeum Betanet Node Setup </h1>

**System Requirements**

|  CPU  |    RAM     |     SSD    |  
|-------|------------|------------|
|    4  |     16     |    200     |

**Firstly, if you have previously set up node, you need to reset your account from your wallet to remove the stake you made from your Metamask wallet**

*for this,  settings > advanced > reset account*

**If you are setting up for the first time, you must first add the sphinx network to your wallet**
* [Documentation](https://docs.shardeum.org/network/endpoints)

![Screenshot_11](https://user-images.githubusercontent.com/100621008/227813008-6861255d-d594-47f3-9dd8-d5906d939ea2.jpg)

*System Update*
```
sudo apt update && sudo apt upgrade -y
```
*Curl installation*
```
sudo apt-get install curl
```
*Docker installation*
```
sudo apt install docker.io -y
```
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
*Validator installation*
```
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh
```
*I leave the ss of the questions you will be asked in the installation, for a clearer understanding*


![Screenshot_1](https://user-images.githubusercontent.com/100621008/227814157-7803ca83-0383-4960-b669-4b717cadc1e1.jpg

![Screenshot_2](https://user-images.githubusercontent.com/100621008/227814201-dad2d78c-4da7-4d59-8afc-6efbad5aa0be.jpg)

