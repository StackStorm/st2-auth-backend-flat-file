## 0.4.0

### Add

 - Added apr1.py module from https://github.com/Tblue/pyapr1 to support
   apr1 hash algorithm.

### Remove

 - Removed passlib dependency since it's been unmaintained for 5 years
   and is causing compatibility issue with bcrypt module.

### Change

 - Used standard library hashlib and crypt to support SHA and CRYPT hash.
