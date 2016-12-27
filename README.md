Public Key Infrastructure
=========================

OpenSSL configuration files and scripts for the most common PKI operations:

* `create` -- Script to create, open, and close an encrypted file-based volume
  on an OpenBSD host. Hard link it as `open` and `close` after the volume is
  created.
* `pkicmd` -- Wrapper around common OpenSSL commands. Create symbolic or hard
  links to call different functions.
* `*.conf` -- OpenSSL configuration templates. These should be placed in the
  same directory and the link that's used to execute `pkicmd`.
