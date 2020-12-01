# Vault
Vault is a shell script that you can use for managing secrets such as passwords, and API key. This project is highly inspired by [pwd.sh](https://github.com/drduh/pwd.sh).

## Usage
- Store secret with key: `$ ./vault.sh store <key> '<secret>'`
- Copy secret to clipboard: `$ ./vault.sh get <key>`
- Delete secret by its key: `$ ./vault.sh delete <key>`
- List all secret `$ ./vault.sh list`

## Todo
- [ ] Use GPG
- [x] List all secret key
- [x] Delete secret by key
- [ ] Delete all secret

## License
Licensed under [The MIT License](https://github.com/maarlf/vault/blob/master/LICENSE).
