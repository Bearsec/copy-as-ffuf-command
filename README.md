# Copy as FFUF Command

Burp Suite extension for FFUF command generation.

## Modify the request to place the FUZZ keyword on the request

![1](https://github.com/phlmox/burp_copy_as_ffuf_command/assets/62145317/797ea794-8704-4ec5-a755-787ef5a4de2a)

## Right click and choose the Copy as FFUF Command from Context Menu

![2](https://github.com/phlmox/burp_copy_as_ffuf_command/assets/62145317/64fd7e77-0ac9-4460-a6b1-6e0cd06d332c)

## Command is copied to your clipboard

![3](https://github.com/phlmox/burp_copy_as_ffuf_command/assets/62145317/b38f9693-f861-4cfb-a083-e0dcd5d55915)

# Modification

Modified _burp_ffuf_copy.py_
- Available from context menu in **Repeater**, **Proxy HTTP History**, and **Logger** tabs.
- Includes the **Host** header in the generated command.

# Installation

You can manually install the extension into Burp Suite:

1. **Download the extension file** from the [Releases](https://github.com/Bearsec/copy-as-ffuf-command/releases) section or directly from the link below:
   👉 [Download copy_as_ffuf_bsmod.bapp](https://github.com/Bearsec/copy-as-ffuf-command/releases/download/v.1.0.0/copy_as_ffuf_bsmod.bapp)
2. Open **Burp Suite** and go to:
   ```
   Extensions → BApp Store → Manual Install (bottom-left)
   ```
3. Select the downloaded `.bapp` file to install it.

## Notes

- ⚠️ This release **does not have a BApp Store signature**. Burp Suite will show a warning when installing it.
- ⚠️ Use at your own risk. The author of the modification is not responsible for its functionality.

# Credits

Original project by: [phlmox](https://github.com/phlmox/burp_copy_as_ffuf_command)  

Modified version maintained by: [Bearsec](https://github.com/Bearsec)
