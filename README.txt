HERBAL APK WEBSITE - READY TO DEPLOY

WHAT TO DO NEXT
1. Replace app-release.apk with your real release APK file.
2. If your APK filename is different, update both links in index.html:
   href="app-release.apk"
3. Update the version in script.js.
4. Upload this whole folder to Firebase Hosting.

FIREBASE HOSTING QUICK STEPS
1. Install Firebase CLI
2. Login: firebase login
3. In your project folder: firebase init hosting
4. Set the public folder to this folder's contents
5. Deploy: firebase deploy

NOTES
- Firebase Hosting is designed for static web content and deploys files from the directory set as the public folder.
- The public directory in firebase.json controls which files are deployed.
