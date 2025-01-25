# Markdown Cheat Sheet

## 1. Başlıklar (Headings)
```markdown
# Başlık 1
## Başlık 2
### Başlık 3
#### Başlık 4
##### Başlık 5
###### Başlık 6
```

# Başlık 1  
## Başlık 2  
### Başlık 3  
#### Başlık 4  
##### Başlık 5  
###### Başlık 6  

---

## 2. Kalın ve İtalik Yazı
```markdown
**Kalın Yazı**  
*İtalik Yazı*  
***Kalın ve İtalik Yazı***  
```

**Kalın Yazı**  
*İtalik Yazı*  
***Kalın ve İtalik Yazı***

---

## 3. Listeleme

### Düzenli Liste (Numbered List)
```markdown
1. Birinci madde
2. İkinci madde
    1. Alt madde
    2. Alt madde
3. Üçüncü madde
```

1. Birinci madde  
2. İkinci madde  
   1. Alt madde  
   2. Alt madde  
3. Üçüncü madde  

### Düzeniz Liste (Bulleted List)
```markdown
- İlk madde
- İkinci madde
  - Alt madde
  - Alt madde
- Üçüncü madde
```

- İlk madde  
- İkinci madde  
  - Alt madde  
  - Alt madde  
- Üçüncü madde  

---

## 4. Linkler
```markdown
[Bağlantı Adı](https://example.com)  
[Google'a Git](https://google.com)  
```

[Bağlantı Adı](https://example.com)  
[Google'a Git](https://google.com)

---

## 5. Görseller
```markdown
![Görsel Açıklaması](https://via.placeholder.com/150)
```

![Görsel Açıklaması](https://images.pexels.com/photos/247599/pexels-photo-247599.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940)

---

## 6. Kod Blokları

### Tek Satır Kod
```markdown
`Bu bir kod satırıdır.`
```

`Bu bir kod satırıdır.`

### Çok Satırlı Kod
```markdown
```
Bu birden fazla
satırlı kod bloğudur.
```
```

```
Bu birden fazla
satırlı kod bloğudur.
```

---

## 7. Tablo
```markdown
| Başlık 1    | Başlık 2    | Başlık 3    |
|-------------|-------------|-------------|
| Veri 1      | Veri 2      | Veri 3      |
| Veri 4      | Veri 5      | Veri 6      |
```

| Başlık 1    | Başlık 2    | Başlık 3    |
|-------------|-------------|-------------|
| Veri 1      | Veri 2      | Veri 3      |
| Veri 4      | Veri 5      | Veri 6      |

### Tablo Özelleştirme

#### Hücre Hizalaması

- **Solda hizalama:** `:---`
- **Ortada hizalama:** `:---:`
- **Sağda hizalama:** `---:`

```markdown
| Sol Hizalı  | Ortada Hizalı | Sağ Hizalı  |
|:------------|:-------------:|------------:|
| Sol         | Orta          | Sağ         |
| Sol         | Orta          | Sağ         |
```

| Sol Hizalı  | Ortada Hizalı | Sağ Hizalı  |
|:------------|:-------------:|------------:|
| Sol         | Orta          | Sağ         |
| Sol         | Orta          | Sağ         |

---

## 8. Alıntılar
```markdown
> Bu bir alıntıdır.
> İkinci satır alıntı.
```

> Bu bir alıntıdır.  
> İkinci satır alıntı.

---

## 9. Çizgi Çekme
```markdown
---
***
___
```

---
***
___

---

## 10. Görev Listesi
```markdown
- [x] Yapıldı
- [ ] Yapılmadı
- [ ] Üzerinde çalışılıyor
```

- [x] Yapıldı  
- [ ] Yapılmadı  
- [ ] Üzerinde çalışılıyor  

---

## 11. HTML Kullanımı (Opsiyonel)
Markdown içinde HTML kullanabilirsiniz:
```markdown
<div style="color: red;">HTML ile yazılmış bir paragraf.</div>
```

<div style="color: red;">HTML ile yazılmış bir paragraf.</div>

---

## 12. Renkli Metin (HTML ile)
Markdown'da doğrudan renkli metin desteği yoktur, ancak HTML kullanarak renk ekleyebilirsiniz:

```markdown
<span style="color: blue;">Bu mavi bir metindir.</span>
<span style="color: green;">Bu yeşil bir metindir.</span>
```

<span style="color: blue;">Bu mavi bir metindir.</span>  
<span style="color: green;">Bu yeşil bir metindir.</span>

---

## 13. Emoji Kullanımı
Markdown içinde emojiler kullanabilirsiniz (GitHub gibi bazı platformlarda desteklenir):

```markdown
:smile: :heart: :thumbsup: :rocket:
```

😄 ❤️ 👍 🚀

---