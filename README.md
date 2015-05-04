# launchpad
The companion board application and essentials

I will add to the readme as a full build/install takes place in order to highlight all components, requirements, and prereqs.

- Enable eth1 interface `iface eth1 inet dhcp`
- Add this line to /etc/apt/sources.list `deb http://vontaene.de/raspbian-updates/ . main`
- Now run `apt-get update`
- Then install gstreamer and plugins

```apt-get install \
      libgstreamer1.0-0 \
      gstreamer1.0-alsa \
      gstreamer1.0-tools \
      gstreamer1.0-plugins-base \
      gstreamer1.0-plugins-good \
      gstreamer1.0-plugins-bad```
      
