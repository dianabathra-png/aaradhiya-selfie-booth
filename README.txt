Aaradhiya's Food Truck Selfie Booth

Files:
- index.html: mobile-friendly selfie booth with person segmentation and photo download
- truck-background.png: food truck background image

Publishing:
Upload both files to the root of a GitHub Pages repository. Keep the file names unchanged.

Important:
- Camera access requires HTTPS (GitHub Pages provides HTTPS).
- The selfie filter loads MediaPipe from public CDNs, so an internet connection is required on first load.
- The photo is processed in the browser by this page and is not uploaded to a server.
- Test on the actual phones customers will use before printing a QR code.
- Good lighting and a clear separation between the person and background improve segmentation quality.
