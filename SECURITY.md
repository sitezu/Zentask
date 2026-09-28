# security policy

## the short version
i take this seriously. ZenTask runs with normal user permissions, talks to
no servers, collects nothing, and has no update mechanism that downloads
code from anywhere except the GitHub releases page.

## reporting a vulnerability
if you find something, please don't open a public issue for it.
instead: open a private security advisory on this repo
(**Security → Report a vulnerability** button), or mention it in a
discussion and i'll move it to a private advisory.

## what to expect
- i'll reply within a couple of days (usually much faster)
- i'll fix it and ship a new release with the hash + virustotal scan posted,
  same as every release
- i'll credit you in the release notes if you want it

## supported versions
only the latest release (currently 1.0.6) gets fixes. it's a free hobby
project — but honestly, just update, it's two clicks.

## a note on antivirus flags
the exe is unsigned, so false positives happen. before reporting one as a
"vulnerability": upload your file to virustotal and compare the SHA256 with
the one in the README — if they match and VT says 0/68, it's a false
positive on the signature, not a bug in the app.
