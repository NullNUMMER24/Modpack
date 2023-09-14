# Modpack
Download the mods with curl
```Bash
cat mods | xargs -n1 curl -O
```
# Server Setup
1. Install git
```
sudo apt install git
```
2. Clone the repo
```
git clone https://github.com/NullNUMMER24/Modpack.git
```
3. Install Openjdk
```
apt install -y openjdk-8-jre-headless
```
4. Install Forge
```
java -jar forge-1.16.5-36.2.34-installer.jar --installServer
```
5. Agree to the Minecraft EULA
```
echo "eula=true" > eula.txt
```
6. Start the server
```
java -Xmx11G -jar forge-1.16.5-36.2.34.jar nogui
```