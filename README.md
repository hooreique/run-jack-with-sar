# Run JACK with Synchronous Audio Router

A script for Windows PC that runs JACK 2 with Synchronous Audio Router device.

### [Run JACK with SAR.bat](./Run%20JACK%20with%20SAR.bat)

```bat
"C:\Program Files\JACK2\jackd.exe" --realtime --realtime-priority 75 -d "portaudio" --rate 48000 --period 256 --device "ASIO::Synchronous Audio Router"
```
