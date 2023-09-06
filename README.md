# Pwnagotchi Custom UI

This repositry contains the files necessary to change the UI for pwnagotchi + waveshare3 eInk-Display.
Changes apply to hardware display and webUI.

## Example
[!UI example](https://github.com/FamosoMocoso/pwnagotchi_custom_ui/blob/main/example/pwnagotchi_custom-ui_wavshare3.jpg?raw=true)

## How to Use
Download the files from this repository and transfer them to your pwnagotchi as follows:

```
cp view.py /usr/local/lib/python3.7/pwnagotchi/ui
cp base.py /usr/local/lib/python3.7/pwnagotchi/ui/hw
cp waveshare3.py /usr/local/lib/python3.7/pwnagotchi/ui/hw
```
**Please note:** If you are using another Display you need to exchange 'waveshare3.py' and put your modifications into the corresponding display file in that directory 
