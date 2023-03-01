# Texttv i bash

Självklart ska man kunna kasta ett öga på texttv i terminalen om man vill det.

## Instruktioner

1. Sätt miljövariabeln `TEXTTV_APP` till något unikt, annars kommer scriptet att avbrytas. (Lägg till en sån här rad i din `.bashrc`.)

```
export TEXTTV_APP=ettuniktnamnsomjagvaltsjälv
```

2. Se till att scriptet finns i din $PATH, antingen genom att addera sökvägen hit eller genom att kopiera scriptet till din egen bin-katalog.

3. Läs Text-TV genom att skriva `bx` eller `bx sidnr`

Scriptet använder [texttv.nu](texttv.nu) som är utvecklat av programmeraren [Per Thernström](https://texttv.nu/sida/om-texttv-nu)

## Beroenden

Du behöver ha [curl](https://github.com/curl/curl), [jq](https://stedolan.github.io/jq/) och bash. (Som du brukar kunna installera med din pakethanterare (`apt`, `brew`, `chocolatey` etc)).
