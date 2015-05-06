# AS_Volley

1. AndroidManifest.xml 開啟網路權限
#<uses-permission android:name="android.permission.INTERNET" />

2. Copy volley.jar 到專案的 libs 底下

3. 在App/build.gradle 加入下文, 加入後點擊右上角的 [Sync Now]
    
compile files('libs/volley.jar')

4. 簡單測試
