# Gi oss tilgang med SSH-key for en server

## Helt enkelt skal det være å kjøre:
`curl -s https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`
## Eller:
`wget -qO - https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`

## Eller i hetzner consollen som sliter med tegnsetting og innliming
```
wget raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys
cat pubkeys >> .ssh/authorized_keys
```
