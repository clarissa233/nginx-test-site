# Security Fixes

## Forward secrecy
Forward secrecy means that even if your server's private key is stolen in the future, past conversations cannot be decrypted. Without it, all past traffic is at risk.

## OCSP revocation check
OCSP checks whether your certificate has been cancelled or revoked. A revoked certificate means browsers will warn visitors your site is not safe.

## Security headers configuration
Security headers tell browsers how to behave on your site — what content to allow, what information to share, and what features to enable. We check not just that they exist but that they are correctly configured.

## DNS CAA records
DNS CAA records tell the internet which certificate authorities are allowed to issue certificates for your domain. Without them, any authority could issue a certificate for your site.

## Server header hidden
Your server is telling visitors exactly what software it runs and which version. Attackers use this information to find known vulnerabilities. The server software name should be hidden.

## Email security (SPF + DMARC)
Email security records (SPF and DMARC) prevent criminals from sending emails pretending to be from your domain. Without them, anyone can send fake emails that look like they came from you.

## DNSSEC enabled
DNSSEC adds a digital signature to your domain's DNS records. Without it, attackers could redirect your visitors to a fake version of your site without them knowing.
