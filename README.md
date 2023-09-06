# Pwnagotchi Custom UI

This repositry contains the files necessary to change the UI for pwnagotchi + waveshare3 eInk-Display.
Here I added some lines and changed the position and content of some lables.
Changes apply to hardware display and webUI.

## Example
![](https://github.com/FamosoMocoso/pwnagotchi_custom_ui/blob/main/example/pwnagotchi_custom-ui_wavshare3.jpg?raw=true)

## How to Use
Download the files from this repository and transfer them to your pwnagotchi as follows:

```
cp view.py /usr/local/lib/python3.7/pwnagotchi/ui
cp base.py /usr/local/lib/python3.7/pwnagotchi/ui/hw
cp waveshare3.py /usr/local/lib/python3.7/pwnagotchi/ui/hw
```
**Please note:** If you are using another Display you need to exchange `waveshare3.py` and put your modifications into the corresponding display file in that directory

## Bonus
Some costum faces in `custom-faces_config.toml`.
