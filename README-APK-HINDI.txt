LENA-DENA ANDROID APK PROJECT

Yeh Android Studio project hai. Ismein app ka HTML Android WebView ke andar chalega.
Diary entries browser local storage (WebView app data) mein save hongi.

ANDROID PHONE SE APK BANANE KA TARIKA (GitHub Actions):
1. GitHub par naya repository banao, jaise lena-dena-apk.
2. Is ZIP ko extract karo.
3. Is ZIP ke andar ki saari files/folders repository ke root mein upload karo.
   Dhyan rahe .github folder bhi upload hona chahiye.
4. GitHub repository mein Actions tab kholo.
5. 'Build Lena-Dena APK' workflow select karo aur 'Run workflow' dabao.
   Main branch par upload karne ke baad push se bhi build apne aap trigger hoga.
6. Build complete hone par workflow run kholo.
7. Neeche Artifacts mein 'Lena-Dena-APK' download karo.
8. ZIP extract karo. app-debug.apk par tap karke install karo.
   Android pooche to 'Install unknown apps' ki permission allow karni pad sakti hai.

NOTE:
- Yeh debug APK hai, testing/personal use ke liye.
- APK abhi digitally signed release build nahi hai.
- App data isi installed app ke private storage mein rahega. App uninstall/clear data karne par diary data delete ho sakta hai.
- GitHub Pages/website ka localStorage aur installed APK ka data alag-alag hota hai.
