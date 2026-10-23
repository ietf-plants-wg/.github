# IETF PLANTS Working Group

**PKI, Logs, And Tree Signatures**

The PLANTS Working Group is chartered in the IETF Security Area. Its goal is to
reduce the overhead of large post-quantum signatures in Public Key Infrastructure
(PKI) systems that use Certificate Transparency (CT).

Post-quantum signature algorithms produce significantly larger signatures than
classical algorithms. This becomes costly when integrating Certificate
Transparency into PKI operations. PLANTS addresses this by integrating log
construction into certificate issuance and developing Merkle Tree-based
certificate constructions, allowing a single signature to cover multiple
key/identifier bindings.

## Work Items

- **Merkle Tree Certificates** —
  [`draft-ietf-plants-merkle-tree-certs`](https://datatracker.ietf.org/doc/draft-ietf-plants-merkle-tree-certs/)
  — Reduces CT logging overhead while maintaining security properties comparable
  to X.509 and Certificate Transparency.
- **Deployment Use Cases** -
  [`draft-ietf-plants-deploy-use-cases`](https://datatracker.ietf.org/doc/draft-ietf-plants-deploy-use-cases/)
  - Explores when and how MTC in parts or full can be used in different use cases.

## Resources

| Resource | Link |
|----------|------|
| WG page | https://datatracker.ietf.org/wg/plants/about/ |
| Mailing list | plants@ietf.org |
| Mailing list archive | https://mailarchive.ietf.org/arch/browse/plants/ |
| Document tracker | https://datatracker.ietf.org/wg/plants/documents/ |

## Participation

PLANTS is open to all. To participate:

- Subscribe to the [mailing list](https://mailman3.ietf.org/mailman3/lists/plants@ietf.org)
- Attend IETF meetings (the WG meets at each IETF meeting)
- Review and comment on [working group documents](https://datatracker.ietf.org/wg/plants/documents/)
- Contribute via GitHub issues and pull requests in this organization

All contributions to IETF documents are subject to the
[IETF Note Well](https://www.ietf.org/about/note-well/).

## Repositories

Each working group document has its own repository in this organization. Issues
and pull requests for editorial suggestions and technical discussion are welcome.

## Note Well

By participating in IETF activities, you agree to the terms of the
[IETF Note Well](https://www.ietf.org/about/note-well/). Please review it
before contributing.
