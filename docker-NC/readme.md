
**Spin up a Digital Ocean VPS**

Tested on a linux guest Debian 8.0 and Vagrant 1.7.2

 1. Setup environment variable DO_TOKEN with your Digital Ocean Personal Access Token
```
export DO_TOKEN={YOUR_PERSONAL_ACCESS_TOKEN}
```

2. Open the Vagrantfile and make sure values of provider.image and provider.size suit your needs

3. Spinup the VPS
```
vagrant up --provider=digital_ocean
```