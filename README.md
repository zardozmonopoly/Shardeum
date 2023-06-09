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

*In the 3rd ss, you write a password you set and write it down somewhere because we will use that password to enter the dashboard*

*After selecting port 8080, say enter to the incoming questions and pass*

![Screenshot_1](https://user-images.githubusercontent.com/100621008/227814368-009ddf39-c092-4320-a72b-f69671b038ef.jpg)

![Screenshot_2](https://user-images.githubusercontent.com/100621008/227814452-f7f65888-253c-476c-90e6-f9299ec142fb.jpg)

![Screenshot_3](https://user-images.githubusercontent.com/100621008/227814590-9f6c6b0c-2afd-4ee0-a6ea-76a963746c5e.jpg)


![Screenshot_4](https://user-images.githubusercontent.com/100621008/227816505-88b4ffeb-9170-4a34-81b7-334336a5bebb.jpg)


![Screenshot_5](https://user-images.githubusercontent.com/100621008/227816513-b184e7e2-713b-4478-bbfe-07626faa5e78.jpg)


![Screenshot_6](https://user-images.githubusercontent.com/100621008/227816529-b84dddd6-b134-4063-8c4b-79e04e3da71a.jpg)


![Screenshot_7](https://user-images.githubusercontent.com/100621008/227816540-96c9ac38-bc7b-4685-b523-b9b967a5a510.jpg)

*When you get the result as in the following ss, the installation is finished without any problems*

![Screenshot_8](https://user-images.githubusercontent.com/100621008/227817229-6ead9283-d07f-43da-b5ec-efebb5317973.jpg)

*Start Node*
```
$HOME/.shardeum/shell.sh
```
```
operator-cli gui start
```
*Explorer and wallet operations*
*first we need SHM token to stake our wallet and we get it by tweeting or from Shardeum discord faucet*
* [Faucet with twit](https://faucet-sphinx.shardeum.org/)
* [Discord Faucet](https://discord.com/channels/933959587462254612/1070780355931541514)

*Type your IP address here https://yournodeIP:8080 ,enter it in the browser and enter it and we'll get to the dashboard section,you will see warnings on the page that opens, but we will skip the warnings and continue and reach the dashboard*

*This screen will greet you first and we will need to type the password we just created in the node*

![Screenshot_9](https://user-images.githubusercontent.com/100621008/227820048-8143b73d-1c85-4773-ba48-7a02ca13d11d.jpg)

*After logging into the dashboard, we need to stake the SHM tokens we receive and we will do the following operations in order*

![1679881735578](https://user-images.githubusercontent.com/100621008/227822785-c5f5d086-e7e8-4cf2-a4b7-6cd1f84c6a0d.jpg)

![1679881648651](https://user-images.githubusercontent.com/100621008/227822828-1bdc1366-1700-4f35-bb85-2823395a5426.jpg)

*The minimum staking rate here is 10 SHM*

![1679881904847](https://user-images.githubusercontent.com/100621008/227823152-e696945a-5b16-4b16-8d86-8783b1ba473d.jpg)

![1679881816713](https://user-images.githubusercontent.com/100621008/227823181-b4fb7455-1879-43d8-8e4d-21fe26f3a63e.jpg)

![1679881786355](https://user-images.githubusercontent.com/100621008/227823222-f395000e-f327-4dc8-9a7b-7125d92ff7d8.jpg)

*Nodes can stay on standby for a long time because they are active in sequence. This does not mean that your node is not working...It can become standby after being active, this is not about you but about the operation of the system*

















