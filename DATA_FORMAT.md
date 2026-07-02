# Veri Formatı

Bu doküman, ürün, marka ve kategori önerilerinin paylaşılması için kullanılacak basit veri formatını açıklar.

## Kategori

```json
{
  "id": "ekmek",
  "name": "Ekmekler",
  "emoji": "🍞"
}
```

## Marka

```json
{
  "id": "ornek_marka",
  "name": "Örnek Marka",
  "initials": "ÖM",
  "description": "İsteğe bağlı açıklama"
}
```

## Ürün

```json
{
  "id": "ornek_marka_ornek_urun",
  "name": "Örnek Ürün",
  "brand": "Örnek Marka",
  "categoryId": "ekmek",
  "status": "conditional",
  "note": "Etiket kontrolü önerilir"
}
```

## Durum Değerleri

- `approved`: Onaylı
- `conditional`: Koşullu
- `warning`: Dikkat

## Katkı Notu

Ürün önerilerinde mümkünse ürün adı, marka adı, kategori ve etiket bilgisi birlikte paylaşılmalıdır.
