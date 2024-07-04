# DHS SVIP Interoperability Testing Metadata

Repository of machine-readable artifacts related to W3C Verifiable Credentials and W3C Decentralized Identifiers, for use in W3C VC/DID interoperability testing with DHS.

These include:

- JSON-LD @context file(s) & associated cryptographic digest(s); in the /contexts directory
- Bitstring status list(s); in the /status directory
- DID document(s); in the /ddocs directory

## Directory Structure

/ns
- /cbp
  - /contexts
  - /status
  - /ddoc
- /uscis
  - /contexts
  - /status
  - /ddoc


> [!IMPORTANT]  
> You should confirm that the hexadecimal encoded SHA2-256 digest value of a @context file matches our published digest value prior to using.

- We use the following file naming convention to publish the digest values:
   - @context file e.g. citizenship-uscis-vcb-v1.jsonld
   - associated digest file e.g. citizenship-uscis-vcb-v1-digest.txt

Steps:
1. Run the command *'curl -s https://url-of-the-context-file | openssl dgst -sha256'* from a modern Unix command line interface to generate the cryptographic digest of the context file
2. Ensure that the digest generated in the prior step matches the one found in the associated published digest file



