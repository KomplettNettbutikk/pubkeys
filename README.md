# Gi oss tilgang med SSH-key for en server

## Helt enkelt skal det være å kjøre:
`curl -s https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`
## Eller:
`wget -qO - https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`

## Eller om vi har mistet tilgang til en Hetzner server:
1. Reset root passord.
2. Logg inn med console i Hetzner GUI, bruk passordet
3. Hent ned ssh-keys slik som beskrevet:
```
wget raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys
cat pubkeys >> .ssh/authorized_keys
```
