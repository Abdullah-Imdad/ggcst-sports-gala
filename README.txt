GGCST SPORTS GALA - setup (Roman Urdu)

1) Firebase Console > Authentication > Sign-in method > Email/Password ON.
   Users tab > Add user: apni developer email+password, aur admin email+password banayein.
2) index.html me sirf is line ko apni emails se badlein:
   const CFG={dev:["DEVELOPER_EMAIL@example.com"],admins:["ADMIN_EMAIL@example.com"]}
3) firestore.rules ke andar wohi emails (chhoti letters me) likhein.
   Firebase Console > Firestore Database > Rules > poora text paste karke Publish.
4) GitHub par naya repository banayein (Public), in sab files ko upload karein.
   Settings > Pages > Deploy from branch > main > /root > Save.
5) 1-2 minute baad link ban jayega (username.github.io/repo-name). Phone me kholkar
   "Add to Home screen / Install app" karein.
