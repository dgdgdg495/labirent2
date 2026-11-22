LABIRENT ORYANTIRING - Android projesi
1) Android Studio'yu ac: File > Open > bu klasoru sec (LabirentOryantiring).
2) Sync bitince: Build > Build Bundle(s) / APK(s) > Build APK(s).
3) APK: app/build/outputs/apk/debug/app-debug.apk  (telefona kopyalayip kur)
Oyun dosyasi: app/src/main/assets/index.html (degistirirsen tekrar derle)
Yatay ve dikey donme acik, ekran acik kalir, geri tusu oyunu duraklatir.

GITHUB ILE ONLINE DERLEME:
- Klasorun ICERIGINI GitHub deposuna yukle.
- .github klasoru yuklenmezse: Add file > Create new file, ad olarak  .github/workflows/build.yml  yaz, build-workflow-kopya.yml icerigini yapistir.
- Actions sekmesi > APK Derle > Run workflow > bitince Artifacts: LabirentOryantiring-APK (zip icinde app-debug.apk).
