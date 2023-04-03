# bro-otx
Integrate Bro with Alienvault OTX

Installation
------------

Unzip the project into the site folder of zeek; eg of path: /opt/bro/share/bro/site/

Add the following to your local.zeek: @load site/otx

Add your api key to the bro-otx.conf configuration file. 

Allow the bro-otx.py script have the ability to write to your zeek scripts directories.
