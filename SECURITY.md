# Security Policy

It is strongly recommended to establish a [security policy](https://imagemagick.org/script/security-policy.php) suitable for your local environment before utilizing ImageMagick. There is also a [development container](https://containers.dev/) available in the `.devcontainer/security` folder that can be used to verify that the security issue can be reproduced with the latest source code and the suggested security policy.

## Supported Versions

We encourage users to upgrade to the latest ImageMagick release to ensure that all known security vulnerabilities are addressed.  On request, we can backport security fixes to other ImageMagick versions.

## Reporting a Vulnerability

Before you post a vulnerability, first determine if the vulnerability can be mitigated by the security policy.  ImageMagick, by default, is open. Use the security policy to add constraints to meet the requirements of your local security governance.  If you feel confident that the security policy does not address the vulnerability, post the vulnerability as a [security advisory](https://github.com/ImageMagick/ImageMagick/security/advisories/new).  Most vulnerabilities are reviewed and resolved within 48 hours.
