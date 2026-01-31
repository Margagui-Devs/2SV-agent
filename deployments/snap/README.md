# Deployment with Snap Store

By browsing to the Snap Store, you'll be able [to find our own snap `2SV Agent`](https://snapcraft.io/2SVio). You can either install the `2SV Agent` through the command line.

     snap install 2SVio

Or use the Desktop client to have a visual interface.

![2SV Agent on Snap Store](./snapstore.png)

Once installed you can find your 2SV Agent configration at `/var/snap/2SVio/common`. Run the 2SV Agent as following.

    sudo 2SVio.agent -action=run -port=80

If successfull you'll be able to browse to port `80` or if you defined a different port. This will open the 2SV Agent interface.
