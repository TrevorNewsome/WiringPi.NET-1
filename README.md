# WiringPi.Net
WiringPi's library .NET/Mono Wrapper

This is a simple .NET wrapper around Drogon's great library [WiringPi](http://wiringpi.com). I needed some simple way to use that library in my Mono application runing under RPi's Raspbian and Odroid's Debian and this is it :)

# How to

1. Checkout WiringPi library:

	* RaspberryPi: `git clone git://git.drogon.net/wiringPi`
	* Odroid: `git clone https://github.com/hardkernel/wiringPi`

2. Build it

```
cd wiringPi
git pull origin
./build
```

3. Check if Shared Object Library has been created:

`ls /usr/local/lib/libwiringPi.so`

4. Now you can use WiringPi in your .NET/Mono projects, just add reference to WiringPi.NET.dll and you should be good to go.