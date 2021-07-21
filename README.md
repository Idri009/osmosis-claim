# osmosis claim script

----

## Requirement

apt install expect -y

## Run

`expect claim.exp  "keyname" "password" "mnemonic" "Votable proposal id"`

## Expected error

|Error          |Description|
|---------------|-----------|
|Timeout        |If timeout occurred have to re-run the application to claim all airdrops.|
|Key Duplication|To delete key `osmosisd keys delete [key name] --keyring-backend file --yes`|





