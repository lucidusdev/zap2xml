## zap2xml.exe binary compatible with gracenote.com



#### Include

- zap2xml.zap2it.exe
  this is the original zap2xml.exe, using `tvlistings.zap2it.com` it's non-working as `zap2it.com` has moved to new `gracenote.com`. There is work around to continue with this `exe`(or keep your old current `zap2xml.exe`) . Please read my post on the ["Cache Spoofing](https://lucidusdev.github.io/2025/05/28/update-zap2xml-for-new-gracenote-com/#Cache-Spoofing)" section.

- zap2xml.opt.exe

  This is my modified version, uses `tvlistings.gracenote.com`, and it's a drop-in replacement for current `zap2xml.exe`. This `zap2xml.exe` also accepts a new `-H` option for future domain change:

  ```
  zap2xml.exe -u user@email.com -p 1234 -H tvlistings.newweb.com ....
  ```

  And here is the detail about [patching the executable binary.](https://lucidusdev.github.io/2025/05/28/update-zap2xml-for-new-gracenote-com/#Patching-the-exe)

