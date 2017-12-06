# Volt
ElectricVolt 
Electric [VOLT, e]

http://Electricvolt.net

What is Electric?

Electric is like Bitcoin, but based on Litecoin. http://Electricvolt.net

License

Electric is released under the terms of the MIT license. See COPYING for more information or see http://opensource.org/licenses/MIT.

Development and contributions

Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.

Frequently Asked Questions

How much VOLT can exist?

Total of 10,000,000,000 coins

How get doge?

Scrypt Proof of Work

1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-100,000 Electric Reward

100,001 — 200,000: 0-50,000 Electric Reward

200,001 — 300,000: 0-25,000 Electric Reward

300,001 — 400,000: 0-12,500 Electric Reward

400,001 — 500,000: 0-6,250 Electric Reward

500,001 - 600,000: 0-3,125 Electric Reward

600,000+ — 1,000 Reward (flat)

make Electricd

sudo apt-get install build-essential \
                     libssl-dev \
                     libdb5.1++-dev \
                     libboost-all-dev \
                     libqrencode-dev \
                     libminiupnpc-dev

cd src/
make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1
