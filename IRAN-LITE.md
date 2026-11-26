# v2rayNG Aghajani Edition — Iran Lite (Android)

Install the ARM64 preview, add your own subscription, choose a server, and start
the Android VPN. A fresh install enables Iran Lite in Routing. To restore the
preset after editing, use **Routing → Import predefined rules → Aghajani Edition -
Iran Lite**.

The preset contains the same Iran domain and IP lists as the Windows edition.
The APK embeds the exact compressed rules from [the v2rayN fork](https://github.com/aghajani82/v2rayN/pull/1)
and uses Xray's IPOnDemand strategy. ipmyp.ir and other Iranian destinations
go direct. Other destinations use the selected proxy. The bundled lists come from
[Chocolate4U/Iran-v2ray-rules](https://github.com/Chocolate4U/Iran-v2ray-rules) (GPLv3)
and [bootmortis/iran-hosted-domains](https://github.com/bootmortis/iran-hosted-domains) (MIT).

The preview uses com.v2ray.ang.aghajani.preview and installs alongside the
official app. It uses a debug signing key. A later preview built on a fresh
runner may require uninstalling this preview first. A distribution release
should use the separate release app ID and a durable release signing key.

## bootmortis MIT notice

Copyright (c) 2022 bootmortis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
