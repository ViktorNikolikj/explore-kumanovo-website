# Explore Kumanovo Website

Static website for GitHub Pages.

## Before publishing
1. Replace every `[PLACEHOLDER]` in HTML files, especially legal name, email, address, refund terms and privacy details.
2. Have Terms, Privacy and Refund pages reviewed for actual operations and North Macedonian requirements.
3. Insert the **official AgentaOS badge** supplied by AgentaOS; do not imitate it.
4. Confirm AgentaOS approval and wording regarding Merchant of Record before enabling checkout.
5. Prices are the six combinations shown in the provided package image, in MKD. If checkout uses EUR, disclose the conversion and final price clearly.
6. Demo partner login should be created in the real app with fake data and limited permissions; never commit credentials to a public repository.

## Publish
Upload the files to the repository root. Settings > Pages > Deploy from branch > main / root. Test the github.io URL.
Then add your custom domain in GitHub Pages settings, and configure DNS at your registrar following GitHub's official documentation. Preserve MX/TXT mail records. Enable Enforce HTTPS when available.

The website itself has no payment integration or server-side login.
