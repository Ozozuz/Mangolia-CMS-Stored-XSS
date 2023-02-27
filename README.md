# Mangolia CMS <= 6.2.19 Stored Cross Site Scripting
------------
Vulnerability
Stored Cross-Site Scripting

Affected Products and Versions
Magnolia CMS <= 6.2.19

CVEID:
CVE-2022-33098

CVSSv3.1 Score
6.1 (Medium)

CVSSv3.1 Attack Vector
AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N

Short Description
Magnolia CMS v6.2.19 was discovered to contain a cross-site scripting (XSS) vulnerability via an insure file upload functionality. In detail it was possibile to upload, either as an asset or as the profile picture for a contact, an SVG image containint arbitrary JavaScript code.

Remediation
Update Magnolia CMS to the latest version available

Discoverer
Giulio Garzia (Ozozuz)

Reference
https://nvd.nist.gov/vuln/detail/CVE-2022-33098
https://docs.magnolia-cms.com/product-docs/6.2/Releases/Release-notes-for-Magnolia-CMS-6.2.20.html
