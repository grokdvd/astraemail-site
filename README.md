# AstraEmail website

Static landing page for astraemail.com (Arabic and English), hosted on Vercel.

- The download button goes to https://api.astraemail.com/download. The AstraEmail API counts the visit, then redirects to the APK (GitHub Releases in this repo).
- While no APK is published, the API sends visitors back to /?soon=1 and the page shows a "coming soon" notice.
- No build step: Vercel serves index.html as is.
