# Acid Repo

## Connect

```bash
sudo apt install gpg

curl -fsSL https://0urr-acid.github.io/acid-repo/KEY.gpg | sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/acid-repo.gpg

echo "deb https://0urr-acid.github.io/acid-repo/ ./" | sudo tee /etc/apt/sources.list.d/acid-repo.list

sudo apt update
sudo apt install caddy-acid