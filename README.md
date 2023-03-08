# win11-right-click-menu

### 設定
```reg
reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```

実行後、いずれか
- エクスプローラ再起動
- サインアウトしてサインイン
- 再起動


### 元に戻す
```reg
reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f 
```
