# improved-lamp
Alight Motion - WEB

## Alight Motion 4.4.4.5249 (APK)

El APK original (`com.alightcreative.motion_4.4.4.5249-5249`, minAPI 23) pesa 191 MB, así que está dividido en trozos de 91 MB en la carpeta `apk/`.

Para volver a unirlo:

```bash
cat apk/alight-motion-4.4.4.5249.apk.*.part > alight-motion-4.4.4.5249.apk
```

SHA-256 del APK completo:

```
ab1b98e9a4d84211fedc0f1f03364465a3736966b901567c5e7d15442bfe9f05
```

## Split de librerías nativas (arm64-v8a)

`apk/split_config.arm64_v8a.apk` (53 MB) contiene las librerías nativas `.so` para arm64-v8a del mismo Alight Motion. Va sin dividir porque pesa menos de 100 MB.
