# <img src="https://github.com/PetrichorFlavour/sov3r/assets/138775891/1066cda3-9884-4675-9b84-679af10b83b7" width="32"> sov3r

### `S`imple `O`pen`V`PN`3` Manage`r`
```
                _____
 ___  _____   _|___ / _ __
/ __|/ _ \ \ / / |_ \| '__|
\__ \ (_) \ V / ___) | |
|___/\___/ \_/ |____/|_|
```

A minimalistic manager to use OpenVPN3 profiles with ease. Utilises the client's built-in commands to control sessions.

## Installation
Simply place the [sov3r](https://github.com/PetrichorFlavour/sov3r/blob/main/sov3r)-file in  `"${HOME}".local/bin`.

Make sure a profile.ovpn-configuration has been imported with:  
`openvpn3 config-import --persistent --config <path> --name <name>`

It will ask which profile should be used as default when run for the first time.


## Keys
| Key | Description                             |
| --- | -----------                             |
| <kbd>c</kbd> | Connect/Reconnect              |
| <kbd>l</kbd> | Connect with log               |
| <kbd>d</kbd> | Disconnect config              |
| <kbd>a</kbd> | Disconnect all sessions        |
| <kbd>i</kbd> | Show IP addresses              |
| <kbd>q</kbd> or <kbd>CTRL-C</kbd>| Quit sov3r |

## Pictures
<img src="https://github.com/PetrichorFlavour/sov3r/assets/138775891/5d8f57c5-95d1-4edd-ac2c-8f1cf88aa4f5" width="460">

<img src="https://github.com/PetrichorFlavour/sov3r/assets/138775891/ec6761f9-d959-401c-b4d5-bc17f843cfd0" width="460">
