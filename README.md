# Inat Box CloudStream Repository

Bu depo, `inat-box.cs3` eklentisini doğrudan GitHub üzerinden CloudStream'e dağıtmak için hazırlanmıştır.

## Kurulumdan önce

GitHub'a yükledikten sonra yalnızca aşağıdaki iki dosyada `OWNER/REPO` alanını kendi GitHub kullanıcı adın ve repo adınla değiştir:

- `repo.json`
- `plugins.json`

Örnek: `OWNER/REPO` → `kullaniciadi/inat-box-repo`

Ardından CloudStream'e şu adresi repository olarak ekle:

`https://raw.githubusercontent.com/OWNER/REPO/main/repo.json`

## Dosyalar

- `inat-box.cs3` — hazır eklenti paketi
- `plugins.json` — eklenti manifest/listesi
- `repo.json` — CloudStream repository tanımı

> Repo branch adın `main` değilse JSON dosyalarındaki `main` değerini branch adınla değiştir.
