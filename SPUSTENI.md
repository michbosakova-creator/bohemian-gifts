# Produktový generátor — jak spustit

## 1. Nastavit API klíč

Vytvořte soubor `.env` v adresáři aplikace:

```
FAL_KEY=váš_klíč_z_fal_ai
```

Klíč získáte na: https://fal.ai → Dashboard → API Keys

## 2. Spustit server

```
npm start
```

## 3. Otevřít aplikaci

Otevřete v prohlížeči: http://localhost:3000

---

## Jak aplikace funguje

1. **Nahrajte fotografii** pilníku (JPG/PNG/WEBP)
2. **Vyplňte údaje** o produktu (název, cena, kategorie...)
3. **Přidejte varianty** (různé barvy, zrnitosti)
4. **Vyberte styly** fotografií (bílé pozadí, mramor, lifestyle...)
5. **Klikněte Generovat** — fal.ai vygeneruje sérii fotografií
6. **Přiřaďte fotky** k variantám (záložka "Přiřazení k variantám")
7. **Exportujte CSV** pro Shoptet (záložka "Export CSV")

## Shoptet import

Stažený CSV soubor importujte v Shoptetu:
Administrace → Produkty → Import produktů → nahrát soubor
