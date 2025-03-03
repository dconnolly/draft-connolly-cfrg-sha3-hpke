---
title: "SHA-3 for HPKE"
abbrev: sha3-hpke
category: info

docname: draft-connolly-cfrg-sha3-hpke-latest
submissiontype: IRTF
number:
date:
consensus: true
v: 3
area: ""
workgroup: "Crypto Forum"
keyword:
 - hpke
 - hybrid encryption
 - KDF
 - SHA3
venue:
  group: "Crypto Forum"
  type: ""
  mail: "cfrg@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/cfrg"
  github: "dconnolly/draft-connolly-cfrg-sha3-hpke"
  latest: "https://dconnolly.github.io/draft-connolly-cfrg-sha3-hpke/draft-connolly-cfrg-sha3-hpke.html"

author:
 -
    fullname: Deirdre Connolly
    organization: SandboxAQ
    email: durumcrustulum@gmail.com

normative:
  RFC9180:
  FIPS202: DOI.10.6028/NIST.FIPS.202

informative:

--- abstract

This document defines Secure Hashing Algorithm-3 (SHA-3) options for Hybrid
Public-Key Encryption (HPKE) as registered KDFs.


--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document requests/registers three new entries to the "HPKE KDF
Identifiers" registry.

Value:
: 0x0004 (please)
KDF:
: SHA3-256
Nh: The output size of the Extract function in bytes
: 32
Reference:
: {{FIPS202}}

Value:
: 0x0005 (please)
KDF:
: SHA3-384
Nh: The output size of the Extract function in bytes
: 48
Reference:
: {{FIPS202}}

Value:
: 0x0006 (please)
KDF:
: SHA3-512
Nh: The output size of the Extract function in bytes
: 64
Reference:
: {{FIPS202}}


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
