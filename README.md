# genus3specialdata


* Baskerville @ 96 all up to 2^16
 
* Saint-Germain @ 48 last 450- up to 2^16

* Legendre @ 32 300-450 up to 2^16

* Baskerville-2: 288 -300, 408-450, 546-608

# hash:

```
def get_filename(disc, fh):
    return "/home/edgarcosta/genus3/%d-%s.ldata" % (disc, hashlib.md5(str(fh)).hexdigest())
```
