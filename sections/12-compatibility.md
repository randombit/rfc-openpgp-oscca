#  Compatibility Profiles

## OSCCA SM234 Profile

The "OSCCA SM234" profile is designed to be compliant to OSCCA regulations.
A compliant OpenPGP implementation **MUST** implement the following
items as described by this document:

* SM2 Recommended Curve ((#sm2-curve))
* SM2 (SM2DSA and SM2PKE) ((#sm2-algorithm))
  * The hash function selected in SM2DSA and SM2PKE **MUST** also be
  OSCCA-compliant, such as SM3 [@SM3]
* SM3 ((#sm3-algorithm))
* SM4 ((#sm4-algorithm))
