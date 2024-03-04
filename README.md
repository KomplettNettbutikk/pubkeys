# Give our devs access to your server like this

## Run this in the linux terminal for the user you want to grant access for:
`curl -s https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`

Or:
`wget -qO - https://raw.githubusercontent.com/KomplettNettbutikk/pubkeys/main/pubkeys >> ~/.ssh/authorized_keys`

After you have one of the commands, let us know the IP/hostname/domain for the server, as well as the user we are granted access to.


## What does the above commands do?
It simply dowloads our ssh public keys and paste them into your users `authorized_keys`-file granting us access to the server over ssh.


## You want to remove access after the job is done?
No problem. Edit your `authorized_keys` file and remove our keys. Then save. We now do not have access to the server anymore.


