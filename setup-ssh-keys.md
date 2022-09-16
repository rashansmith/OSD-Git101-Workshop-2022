# How to setup your SSH Key with GitHub

### Note: 
- You do not need to complete this step if you are using GitHub Desktop
- If using a WINDOWS MACHINE, please use Git CMD instead of the command prompt

## Step 1: Generate your SSH Key on your local Computer
1. In your terminal go into the ssh folder by running: ```cd ~/.ssh```
![cd-ssh](https://user-images.githubusercontent.com/6632748/190640546-c9e6c729-1735-44a0-a89f-f9035e67b260.png)

2. In your current terminal (if you don't already have an ssh-key generated), generate an ssh-key by using the command: ```ssh-keygen -t rsa -b 4096 -C "your_email@example.com"```
  - You will be asked to provide an location to save the key. Press ENTER to leave this bank - it will use the current location
  - You will be asked to enter a passphrase. You can skip this step if you wish by pressing ENTER
  ![Screenshot from 2022-09-16 08-26-40](https://user-images.githubusercontent.com/6632748/190640695-2b03e3d1-72d8-4444-9e2d-587c31eae2b3.png)
3. In your current terminal, view your ssh-key by running ```cat id_rsa.pub```
   ![Screenshot from 2022-09-16 08-27-00](https://user-images.githubusercontent.com/6632748/190641658-113990ba-e59e-4530-ab61-8f07038fa5a4.png)

4. Copy the results of the previous command (you will need this later on)


## Step 2: Add your SSH Key to GitHub
1. In your GitHub account, click on your icon in the upper right corner, and go to:
   - Settings -> SSH and GPG Keys
2. Click the Green Button labeled "New SSH Key"
3. Add a title for your key, and paste the contents of your key from the previous section, in the 'Key' Section
4. Click the Green Button labelled 'Add SSH Key'
![Screenshot from 2022-09-16 08-27-24](https://user-images.githubusercontent.com/6632748/190641815-6b06d849-119b-4430-a1f5-ad54285cd9a0.png)


Additional Instructional Resources:
- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- https://medium.com/devops-with-valentine/2021-how-to-set-up-your-ssh-key-for-github-on-windows-10-afe6e729a3c0
- https://www.inmotionhosting.com/support/server/ssh/how-to-add-ssh-keys-to-your-github-account/

