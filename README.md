# genus3specialdata


* Baskerville @ 96 all up to 2^16
 
* Saint-Germain @ 48 last 200 up to 2^16

# hash eg:

```
def get_filename(disc, fh):
    return "/home/edgarcosta/genus3/%d-%s.ldata" % (disc, hashlib.md5(str(fh)).hexdigest())
```
