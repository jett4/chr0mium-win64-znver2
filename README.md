# chr0mium-win64-znver2
Chromium for Windows 64Bit with Zen 2 Optimizations

### Stable Builds
Requires at least a Zen2 AMD CPU (e.g. AMD Ryzen 3***(X))

### Config (see BUILD.gn for full config)
- march=znver2, thinlto, wpo, lld
- nosync, no widevine, no reports, no debug symbols
- proprietary codes: e.g. aac, mp3, h264
- using vs2019
