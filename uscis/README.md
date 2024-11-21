## Test USCIS DID

- `did:web:dhs-svip.github.io:ns:uscis:oidp`

## Test Sample Credentials 

1. [test-natcert-good-ecdsa-signed.jsonld](test-natcert-good-ecdsa-signed.jsonld) (JOHN DOE - Positive Test)
  - Good VC with ecdsa-rdfc-2019 proof.
2. [test-natcert-revoked-ecdsa-signed.jsonld](test-natcert-revoked-ecdsa-signed.jsonld) (NOELLE WILSON - Negative Test)
  - Good signature but revoked VC with ecdsa-rdfc-2019 proof.
3. [test-natcert-bad-sig-ecdsa-signed.jsonld](test-natcert-bad-sig-ecdsa-signed.jsonld) (NOLAN THOMAS - Negative Test)
  - Bad signature VC with ecdsa-rdfc-2019 proof.
4. [test-natcert-good-ecdsa-bbs-signed.jsonld](test-natcert-good-ecdsa-bbs-signed.jsonld) (JILL SMITH - Positive Test)
  - Good VC with with ecdsa-rdfc-2019 and bbs-2023 proof set.
5. [test-natcert-good-ecdsasd-bbs-signed.jsonld](test-natcert-good-ecdsasd-bbs-signed.jsonld) (JACK TAYLOR - Positive Test)
  - Good VC with ecdsa-sd-2023 and bbs-2023 proof set.

