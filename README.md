# Create private/public keys

## ssh-keygen -t rsa -b 4096 -f ~/.ssh/id_rsa -C your@email.address -N ''

### certs are stored in .ssh subdirectory of ~

# Simple: just run: ssh-keygen

## uses default settings to create private/public key

# Permission on a private key should be: 

##chmod 400 ~/.ssh/yourkey.pem

