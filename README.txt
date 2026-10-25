EstateFlow browser demo — property photo uploads

Files
- index.html: app layout and styling
- app.js: dashboard, listings, photo upload/gallery, leads and settings

Run locally
Open index.html in a modern browser. No build command or package installation is required.

Property photos
- Add or edit a property, choose up to 5 photos (JPG, PNG, WebP), preview them, remove any, then save.
- Images are resized/compressed in the browser and stored in this browser's localStorage alongside demo data.
- This is a single-browser demo. It does not upload images to a server or share them across devices/users. For production, connect a backend and object storage such as Supabase Storage or S3, with authentication and access rules.

Deploy on Vercel
1. Push index.html, app.js and README.txt to the root of your GitHub repository.
2. Go to https://vercel.com/new and import the estateflow repository.
3. Framework Preset: Other. Root Directory: ./
4. Build Command: leave empty. Output Directory: .
5. Install Command: leave empty. Click Deploy.
6. Open the .vercel.app URL shown when deployment finishes.
