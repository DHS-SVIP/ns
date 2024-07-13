# DHS SVIP Interoperability Testing Metadata

Repository of machine-readable artifacts related to W3C Verifiable Credentials and W3C Decentralized Identifiers, for use in W3C VC/DID interoperability testing with CBP & USCIS.

## Test DIDs

- CBP/OT: `did:web:dhs-svip.github.io:ns:cbp:ot`
- USCIS/OIDP: `did:web:dhs-svip.github.io:ns:uscis:oidp`

## Directory Structure

- JSON-LD @context file(s) & associated cryptographic digest(s); in .../contexts 
- Bitstring status list(s); in .../status 
- DID document(s); in .../cbp/ot & .../uscis/oidp

/ns
- /cbp
  - /contexts
  - /status
  - /ot
- /uscis
  - /contexts
  - /status
  - /oidp

## Notes

> [!IMPORTANT]  
> You should confirm that the hexadecimal encoded SHA2-256 digest value of a @context file we publish matches our published digest value.

We use the following file naming convention to publish the digest values:
  - @context file e.g. citizenship-uscis-vcb-v1.jsonld
  - associated digest file e.g. citizenship-uscis-vcb-v1-digest.txt
