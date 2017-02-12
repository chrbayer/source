# Omega2/Omega2+ custom LEDE-image

This is just an attempt at making a reasonably-good starting-point for making custom firmware-images for the Omega2/Omega2+. The default configuration includes things like e.g. avahi for network-discovery, LuCI, instead of the official Onion Console, for easy configuration of things via web-browser, swap-utils and block-mount, for those who wish to take advantage of extroot and so on. It also sets up an access-point, similar to the official firmware, after configuration-reset or upon first run after flash (password '12345678')

Under Ubuntu you should be able to just run first_time_setup.sh and it'll take care of setting things up, after which all you need to do is run 'make'
