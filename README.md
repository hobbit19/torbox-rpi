# torbox-rpi

<b>TorBox (Raspberry Pi)</b>

TorBox is the easy and secure way to host your own Tor .onion hidden service on your own private dedicated portable hardware with a simple to use content management system for publishing your anonymous, dynamic and responsive website or blog etc. and a graphical system administration tool for changing the .onion hostname etc.

You can connect TorBox to any Ethernet port of any router anywhere in the world and without forwarding any ports or changing any domain name records etc. it will always be accessible by it's current .onion hostname.

<b>Requirements:</b>

Raspberry Pi Model 3 B<br>
Clean install of Raspbian Lite (With the standard user: pi and password: raspberry and no updates)<br>
SSH Initially enabled<br>
Internet connection via Ethernet<br>

<b>Installation:</b>

TorBox is designed to be installed headless.

SSH To your Raspberry Pi home directory<br><br>
(If you have already downloaded the zip file to your home directory you can skip the step below)<br><br>
From the terminal run: wget https://github.com/eclipsewebservices/torbox-rpi/raw/master/torbox-rpi.zip<br><br>
From the terminal run: unzip torbox-rpi.zip<br><br>
From the terminal run: cd torbox-rpi<br><br>
From the terminal run: chmod 755 install.sh<br><br>
From the terminal run: sudo ./install.sh<br>

For security there is no access to TorBox from within your local area network, TorBox can only be accessed by using the Tor browser over the Tor network. To login to the underlying operating system you will have to physically connect a keyboard and monitor and use the username: pi and your current TorBox system administration password.

We hope you enjoy your new found privacy and anonymity using TorBox and if you find it useful please consider helping to support us by spreading the word or donating in Bitcoin to: 1kcrttMQZQSZ9UixDP9BCF59W9Mihgg4X or by PayPal to: eclipsewebservices@protonmail.com

Disclaimer: TorBox or Eclipse Web Services are not associated with or endorsed by the Tor Project. Eclipse Web Services offer absolutely no warranty or support for any software installed on TorBox or take absolutely no responsibility or accept absolutely no liability for the way in which you use TorBox or the content you host on it. Ultimately it is also your own responsibility to ensure your own online privacy, anonymity and security. By using TorBox you agree to the terms and conditions of this disclaimer.

Finally remember to give your .onion hostname to anyone you want to access your site as it will not be indexed by regular search engines such as Google and Bing etc. We would recommend doing this by using a secure encrypted email service such as ProtonMail.
