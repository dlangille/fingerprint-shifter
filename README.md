# fingerprint-shifter

When generating new certs (I use Let's Encrypt with acme.sh), the
fingerprint files used with Postfix need to be updated. This script does
that.

Anvil can then distribute the fingerprint files.

```
[certs dan ~] % cat /var/db/certs-for-rsync/cert-fingerprints/relay_clientcerts
1A:37:E3:DF:16:54:A6:00:8A:1F:9D:FA:62:65:C8:D9:68:64:47:61 cliff.example.org
C3:0E:37:24:A6:C0:53:3F:B6:E6:44:5B:A7:10:FB:3A:C5:F2:CE:49 cliff.example.net
CE:72:9B:07:29:F3:E5:1D:B5:36:D2:1A:CE:B8:8B:75:08:3B:B9:B8 gelt.example.net
FD:BD:32:70:36:F8:12:6C:ED:A4:11:E5:BB:00:C9:62:45:90:3B:ED mailjail.langille.org
49:8C:83:7F:B6:9B:E5:7C:6B:76:3E:16:5D:E8:AB:75:17:BB:DF:C2 supernews.example.net
38:27:86:D9:75:8A:B2:53:90:E6:50:63:8B:60:FF:B6:F1:E9:6F:58 tallboy.example.net
04:61:FD:47:6B:61:C7:E1:D4:27:CB:B4:5A:51:43:5A:BB:D4:51:7D x8dtu.example.net
83:6B:70:BF:2F:E0:E6:1F:51:0D:3A:40:AE:23:06:95:D0:40:36:C4 zuul.example.net
```