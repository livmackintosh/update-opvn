Update-OPVN
===========

Just a lazy script if you can't be fucked SSH'ing into your OpenWRT router to
update the OpenVPN configuration. This will extract the zip but exclude osx and
windows files (yuck), scp them to /etc/openvpn on the server and restart the
service.

Warning
-------
Do NOT use this if you don't know what you're doing. Please only use this if you
can understand the code. I have NOT bothered to adhere to any standards as this
is kind of a trivial script. It also hasn't been tested anywhere other than on my
infrastructure so again, don't expect this to work - it may even screw your shit
up =).

Instructions
------------
1. Set or override the variables inside the script (can't be bothered using cli
   parameters here because I never change them).

2. Run the script with a zip file as the argument (usually openvpn service will
   run using the .conf configuration if there is only one).

Licence
-------
This project is licenced under the GPLv3, see the LICENCE file.
