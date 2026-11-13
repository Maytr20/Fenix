# Fenix


## Reassembling the APK

Download all `fenix.part.*` files into the same directory.

**Windows (CMD / PowerShell):**
```cmd
copy /b fenix.part.* Fenix-restored.apk
```

**Linux:**
```bash
cat fenix.part.* > Fenix-restored.apk
```

After reassembling, `Fenix-restored.apk` will be the original APK and can be installed normally.
