# TreeStore-Packages
Pacotes da loja Tree Store
<br>
<br>
Use isto pra fazer os apks
```xml
<app id="treestoreapps" xmlns:app="http://treestore.setin.com/app/key">
  <app:name label="Nome do App" />
  <app:version number="1.0" />
  <app:icon archive="ic.png" />
  <app:permissions xmlns:ptree="http://treestore.setin.com/app/permissions">
    <ptree:permission permission="android.permission.READ_EXTERNAL_STORAGE" />
  </app:permissions>
</app>
```
<br>
<br>
Estrutura:
<br>
/packages/nomedoapp/info.xml
<br>
/packages/nomedoapp/packages.apk
<br>
/packages/nomedoapp/ic.png ou ic.jpg
