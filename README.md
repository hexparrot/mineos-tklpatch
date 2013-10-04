mineos-tklpatch
===============

Turnkey Linux patch for easily extending Applicances

Follow the foloowing instructions as root on a turnkey-based distribution, preferably. To create your own ISO:

    apt-get update
    apt-get install tklpatch git
    git clone --recursive https://github.com/hexparrot/mineos-tklpatch.git
    wget -O turnkey.iso <url for chosen turnkey base iso>
    tklpatch turnkey.iso mineos-tklpatch
