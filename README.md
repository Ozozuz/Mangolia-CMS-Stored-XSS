# Mangolia CMS <= 6.2.19 Stored Cross Site Scripting
------------
### Vulnerability
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Stored Cross-Site Scripting

### Affected Products and Versions
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Magnolia CMS <= 6.2.19

### CVEID:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CVE-2022-33098

### CVSSv3.1 Score
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.1 (Medium)

### CVSSv3.1 Attack Vector
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N

### Short Description
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Magnolia CMS v6.2.19 was discovered to contain a cross-site scripting (XSS) vulnerability via an insure file upload functionality. In detail it was possibile to upload, either as an asset or as the profile picture for a contact, an SVG image containint arbitrary JavaScript code.

### Remediation
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Update Magnolia CMS to the latest version available

### Discoverer
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Giulio Garzia (Ozozuz)

### Reference
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://nvd.nist.gov/vuln/detail/CVE-2022-33098
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://docs.magnolia-cms.com/product-docs/6.2/Releases/Release-notes-for-Magnolia-CMS-6.2.20.html
