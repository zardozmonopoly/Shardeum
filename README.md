<h1 align="center">Shardeum Betanet Node Setup </h1>

![Shardeum](https://user-images.githubusercontent.com/100621008/227815941-a6e67be0-5496-4c01-9d9f-3b5556149fdf.jpg)


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
In the 3rd ss, you write a password you set and write it down somewhere because we will use that password to enter the dashboard.

![Screenshot_1](https://user-images.githubusercontent.com/100621008/227814368-009ddf39-c092-4320-a72b-f69671b038ef.jpg)

![Screenshot_2](https://user-images.githubusercontent.com/100621008/227814452-f7f65888-253c-476c-90e6-f9299ec142fb.jpg)

![Screenshot_3](https://user-images.githubusercontent.com/100621008/227814590-9f6c6b0c-2afd-4ee0-a6ea-76a963746c5e.jpg)


![Screenshot_4](https://user-images.githubusercontent.com/100621008/227816505-88b4ffeb-9170-4a34-81b7-334336a5bebb.jpg)


![Screenshot_5](https://user-images.githubusercontent.com/100621008/227816513-b184e7e2-713b-4478-bbfe-07626faa5e78.jpg)


![Screenshot_6](https://user-images.githubusercontent.com/100621008/227816529-b84dddd6-b134-4063-8c4b-79e04e3da71a.jpg)


![Screenshot_7](https://user-images.githubusercontent.com/100621008/227816540-96c9ac38-bc7b-4685-b523-b9b967a5a510.jpg)







