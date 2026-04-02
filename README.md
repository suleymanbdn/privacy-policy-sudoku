# Sudoku Bulmaca — Gizlilik Politikası (GitHub Pages)

Bu depo, **Sudoku Bulmaca** uygulamasının gizlilik politikasını barındırır.

## GitHub’a yükleme (push)

Bu klasör ayrı bir git deposu olarak hazırlandı. **GitHub’da oluşturduğun boş repoyu** aşağıdaki gibi bağla ( `REPO_ADI` = senin repo adın):

```bash
cd privacy_policy_site
git remote remove origin   # hata verirse yok say
git remote add origin https://github.com/suleymanbdn/REPO_ADI.git
git push -u origin main
```

Kimlik için GitHub **Personal Access Token** veya **SSH** kullanman gerekir; Cursor/agent senin hesabına senin yerine giriş yapamaz.

## Yayın adresi (GitHub Pages)

Depo ayarlarında **Settings → Pages**:

- **Source:** Deploy from a branch  
- **Branch:** `main` / **folder:** `/ (root)`

Sonra politika şu adreste olur:

**`https://suleymanbdn.github.io/REPO_ADI/`**  
Örnek repo adı `sudoku-privacy` ise: `https://suleymanbdn.github.io/sudoku-privacy/`

`index.html` içindeki GitHub bağlantılarını, gerçek repo adınla güncelle (metinde `sudoku-privacy` geçiyorsa).

## Play Console

Mağaza listesindeki gizlilik politikası URL’si olarak yukarıdaki bağlantıyı kullan.

## Yerel önizleme

`index.html` dosyasını tarayıcıda açarak metni kontrol edebilirsin.
