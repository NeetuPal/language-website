# language-website

### Dotnet
----------
```
sudo apt-get update && \
sudo apt-get install -y dotnet-sdk-8.0
```
### Nodejs
---------
# Download and install nvm:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```
# in lieu of restarting the shell
```
\. "$HOME/.nvm/nvm.sh"
```

# Download and install Node.js:
```
nvm install 22
```

# Verify the Node.js version:
```
node -v # Should print "v22.20.0".
```

# Verify npm version:
```
npm -v # Should print "10.9.3".
```
# Python
---------
#Install Python & pip (if not already installed)
```
sudo apt update
sudo apt install -y python3 python3-pip python3-venv
```
# Create a Virtual Environment (Recommended)
```
cd ~/python-demoapp/src
python3 -m venv venv
source venv/bin/activate
```
```
deactivate
```
```
pip install -r requirements.txt

python run.py
```
