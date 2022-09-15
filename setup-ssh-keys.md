# How to setup your SSH Key with GitHub

### Note: You do not need to complete this step if you are using GitHub Desktop

## Step 1: Generate your SSH Key on your local Computer
1. In your terminal go into the ssh folder by running: ```cd ~/.ssh```
2. In your current terminal, generate an ssh-key by using the command: ```ssh-keygen -t rsa -b 4096 -C "your_email@example.com"```
  - You will be asked to provide an location to save the key. Press ENTER to leave this bank - it will use the current location
  - You will be asked to enter a passphrase. You can skip this step if you wish by pressing ENTER
3. In your current terminal, view your ssh-key by running ```cat id_rsa.pub```
4. Copy the results of the previous command (you will need this later on)


## Step 2: Add your SSH Key to GitHub
1. In your GitHub account, click on your icon in the upper right corner, and go to:
   - Settings -> SSH and GPG Keys
2. Click the Green Button labeled "New SSH Key"
3. Add a title for your key, and paste the contents of your key from the previous section, in the 'Key' Section
4. Click the Green Button labelled 'Add SSH Key'


Additional Instructional Resources:
- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- https://medium.com/devops-with-valentine/2021-how-to-set-up-your-ssh-key-for-github-on-windows-10-afe6e729a3c0
- https://www.inmotionhosting.com/support/server/ssh/how-to-add-ssh-keys-to-your-github-account/

