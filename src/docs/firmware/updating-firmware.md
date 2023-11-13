# Updating Custom Firmware

## Steps

1. If you have Windows installed, boot a Linux live ISO and connect to the internet. If you already have Linux installed, move on to step 2.

  ::: tip
  curl is not installed by default for Ubuntu / Ubuntu distros. To install it, run: `sudo apt update && sudo apt install -y curl`
  :::

2. Open a terminal.
   
3. Run [MrChromebox's firmware utility script](https://mrchromebox.tech/#fwscript).
    * In case you forgot, type `cd; curl -LO mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh` and press Enter.
4. Choose option 1: `Install/Update UEFI (Full ROM) Firmware`, and reboot if successful.

::: danger
**Do not reboot if flash was not successful**
:::
