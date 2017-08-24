SSL Self-signed Certificate
===========================

Generates self-signed SSL certificate.

Role Variables
--------------

Defaults: `defaults/main.yml`

Optional variables:

- `ssl_certificate_subject`: Certificate subject
- `ssl_certificate_days`: Certificate validity, defaults to 365 days
- `ssl_certificate`: Absolute path to save SSL certificate (.crt) to
- `ssl_certificate_key`: Absolute path to save SSL certificate private key (.key) to

Author Information
------------------

This role was created in 2017 by NET2GRID.
