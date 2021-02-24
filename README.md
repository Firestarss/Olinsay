# Olinsay

## How to install

- First install [cowsay](https://opensource.com/article/18/12/linux-toy-cowsay)
- Add `olin.cow` to the cows file created by the cowsay intallation
  - On Ubuntu 20.4 (focal), the folder is `/usr/share/cowsay/cows` by default
- Put the following at the end of the file `~/.bashrc` making sure to replace <message> with... well a message

``` bash
if [ -x /usr/games/cowsay -a -x /usr/share/cowsay/cows/olin.cow]; then
    cowthink -f olin <message>
fi```

There you go! That should work! (Said every programmer ever...)
