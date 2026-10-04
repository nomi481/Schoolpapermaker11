SWAT ISLAMIA PAPER MAKER - PWA PACKAGE
1. Open privacy.html and replace YOUR_EMAIL@example.com with your real email.
2. Go to netlify.com > Add new site > Deploy manually, and drag THIS WHOLE FOLDER (the unzipped folder) onto the page.
3. Open your new https link on a phone in Chrome - you should see "Install app".
4. Go to pwabuilder.com, paste your link, Package for stores > Android, and download the zip.
5. Put the assetlinks.json from that zip INTO THIS FOLDER (next to index.html) and re-deploy on Netlify.
   (The _redirects file already serves it at /.well-known/assetlinks.json.)
6. Upload the .aab file to Google Play Console. Use feature-graphic-1024x500.png as the feature graphic,
   icons/icon-512.png as the app icon, and https://YOURLINK/privacy.html as the privacy policy link.
