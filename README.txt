DEPLOY STEPS
1. MyOwnDB folder -> GitHub repo -> Render "Web Service" (Build: npm install, Start: node server.js)
2. Render > Environment: ADMIN_KEY = <unga secret key>
   (Persistent data venumna: Disk add pannu, mount path /var/data, env DATA_DIR=/var/data)
3. Render URL (https://xxxx.onrender.com) copy pannu
4. EduPath/index.html and MyOwnDB/admin/index.html la "YOUR-APP-NAME.onrender.com" -> unga URL ku maathu
5. EduPath -> GitHub Pages push pannu. Admin page-a unga laptop la mattum open pannu (GitHub la podatha).
