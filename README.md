# FPSDC OpenWork Desktop

OpenWork-derived desktop client selected by ADR-0018. Source has not been imported.

The client connects only to a deployment's Commons AI Gateway and the released
Agent Session Contract. The
eligible upstream boundary is the MIT core outside `ee/`; OpenWork Den, hosted MCP
endpoints, hosted inference, and other source-available or subscription-gated
components are excluded.

See `UPSTREAM_PROVENANCE.md` and the canonical desktop foundation document in the
umbrella architecture before importing code.

Distribution, white-labelling, institutional OIDC and the signed deployment
manifest are defined by
`fpsdc-architecture:docs/clients/Institution-Branded-Client-Distribution-and-Access.md`.

The planned release serves both institution-managed campus endpoints and supported
personal Windows, macOS and Linux computers. Installing this client never enrolls
the computer into the Compute Fabric; that requires a separate authorized worker
or volunteer-compute enrollment.
