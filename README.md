# TtlHorizon

Belirli zamanda süresi dolmuş kayıtların anahtarlarını bulur.

## Girdi

now, entries: key, written, ttl.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python ttlhorizon.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
[
  "a"
]
```
