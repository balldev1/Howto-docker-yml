## INSTALL

Docker

Home-brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install --cask docker

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/admin/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

rm -rf /Applications/Docker.app

brew install --cask docker

rm -rf ~/.docker

————
Dokcer run —name xxxxxx -d -p 8080:80 nginx => create container name , port , image

Docker ps => what container run

Docker stop xxxxxxx

Docker rm xxxcontainerxxxxx

docker-compose -f docker-compose.yml up -d
