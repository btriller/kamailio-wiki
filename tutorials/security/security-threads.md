# Overview of Security issues for SIP routers

    Author of initial tutorial:
    Davy Van De Moere
      <davy.van.de.moere@gmail.com>

An attempt to give a full overview of security risks a SIP Router is
confronted with.

## Security Risks

Quoting shamelessly from [RFC3261 Chapter
26](http://www.ietf.org/rfc/rfc3261.txt):

`SIP is not an easy protocol to secure. Its use of intermediaries, its multi-faceted trust relationships, its expected usage between elements with no trust at all, and its user-to-user operation make security far from trivial.`

Risks:

1\. Registration Hijacking (rfc3261)

2\. Impersonating a Server (rfc3261)

3\. Tampering with Message Bodies (rfc3261)

4\. Tearing Down Sessions (rfc3261)

5\. Denial of Service and Amplification (rfc3261)

6\. Scanning attacks

7\. Session re-use

8\. ...
