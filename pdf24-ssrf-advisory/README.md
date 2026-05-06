# PDF24 SSRF Advisory (Coming Soon)

## Summary
A Server-Side Request Forgery (SSRF) vulnerability was identified in PDF24 Online Tools due to insufficient validation of user-supplied URLs.

## Description
Under certain conditions, the application could be induced to perform server-side requests to internal resources, potentially exposing limited internal service metadata.

Additional testing indicated that the behavior could also be used to interact with internal network services and distinguish responsive internal services from non-responsive ones.

## Impact
- Exposure of internal operational metadata
- Limited internal network interaction/enumeration capability
- No evidence of unauthorized access to other users' private data

## Status
This issue has been reported to the vendor and has been addressed.

## Disclosure
A more detailed advisory may be published after coordinated disclosure, without sensitive exploit details.

## Credits
Discovered by Dinh Ngoc Dung  
https://github.com/bibo318
