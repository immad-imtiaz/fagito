# Fagito

### Setting up local machince (LINUX)
------------------------------------------------------------------------------------------
#### 1- Install nvm so that you can manage node version among different services and clients

Install the build-essential package by running the following 
```sh
sudo apt-get update && sudo apt-get install build-essential
```
Install nvm using cURL
```sh
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```
Now you can install and use any version of node required for a particular app

- To install a particular version
    ```sh
    nvm install 10.0
    ```
- To use a particular version
    ```sh
