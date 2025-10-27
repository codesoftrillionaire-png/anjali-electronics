
Anjali Electronics — Vercel-ready static site
--------------------------------------------
Files:
- index.html            : Single-file public + admin interface
- assets/logo.png       : Your logo (replace with higher-res if needed)

Admin login:
- Username: gulshan
- Password: sudhir

How to deploy on Vercel:
1. Go to https://vercel.com and login (GitHub or Google).
2. Create a new project -> Import -> Upload Folder, then upload this folder.
3. Deploy. The site will be live instantly.
4. Open: https://<your-site>.vercel.app/#/admin to access admin panel.

Local testing:
- Open index.html in a browser and visit #/admin to login.

Notes:
- Data is stored in browser localStorage. Use Export JSON in admin to backup.
- For production multi-user auth, integrate Netlify Identity or Firebase Auth.
