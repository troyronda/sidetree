## Context

Per the [DID Core Spec](https://github.com/w3c/did-core) an `@context` MAY be used to represent a DID Document as Linked Data.

If an `@context` is present, any properties not defined in DID Core, ****MUST**** be defined in this context, or in a DID Method specific one.

For example: 

```json
{
    "@context": [
        "https://www.w3.org/ns/did/v1", 
        "https://identity.foundation/sidetree/context-v1.jsonld",
        "https://example.com/method/specific.jsonld"
    ]
}
```

### usage

Deprecated. DO NOT USE.

### publicKeyHex

A hex encoded compressed public key.

Example:

```json
{
  "id": "did:example:123#JUvpllMEYUZ2joO59UNui_XYDqxVqiFLLAJ8klWuPBw",
  "type": "EcdsaSecp256k1VerificationKey2019",
  "publicKeyHex": "027560af3387d375e3342a6968179ef3c6d04f5d33b2b611cf326d4708badd7770"
}
```
