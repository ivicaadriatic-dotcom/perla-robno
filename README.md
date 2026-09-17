# Perla Notte — Robno Materijalno

<p align="center">
  <img src="assets/logo.png" width="120" alt="Perla Notte logo">
</p>

**Sustav upravljanja zalihama proteinskih napitaka**  
Perla Notte d.o.o. · Split, Hrvatska

---

## O aplikaciji

Offline web aplikacija za evidenciju robnog materijala — ulaz robe po fakturama, prodaja napitaka, stanje zaliha i izvještaji za knjigovodstvo.

**Tehnologija:** Jednofilni HTML · IndexedDB · Chart.js · SheetJS  
**Radi bez interneta** — otvori `perla-notte-robno-final.html` u Chrome-u

---

## Funkcionalnosti

| Modul | Opis |
|-------|------|
| 📊 Nadzorna ploča | Grafikon zaliha, raspodjela, brze akcije |
| 📥 Ulaz po fakturi | Grupiranje po broju fakture, edit stavki |
| 🛍️ Prodaja napitaka | Po danu, filter po mjesecu, PDF/Excel export |
| ⚙️ Otpis / Korekcija | Evidencija gubitaka i korekcija |
| 📦 Stanje zaliha | Trenutno stanje po okusima |
| 📋 Normativi | Min/opt razine zaliha |
| 🏷️ Artikli | Baza proteinskih prahova |
| 🏢 Dobavljači | Polleo Adria d.o.o. i ostali |
| 📈 Izvještaji | PDF po mjesecu s totalima prihoda |
| ⚙️ Postavke | Logo, firma, dark mode |

---

## Artikli

8 okusa Protein Praha (1 pakiranje = 2270g = 84 napitka × 27g):

- Dubai Chocolate · Strawberry · Chocolate-Hazelnut
- Swiss Chocolate Supreme · Cookies & Cream · Vanilla Madagascar  
- Chocolate Jaffa · Chocolate Banana

---

## Korištenje

1. Preuzmi `perla-notte-robno-final.html`
2. Otvori u **Google Chrome**
3. Podaci se automatski spremaju u IndexedDB
4. Backup: Sidebar → **Izvezi bazu** (JSON)

---

## Excel generator

Za obojene Excel tablice za knjigovodstvo:

1. Sidebar → **Izvezi bazu** → spremi JSON
2. Otvori `perla-notte-excel-generator.html`
3. Povuci JSON → klikni **Preuzmi SVE tablice**

---

*Perla Notte d.o.o. · Split · 2026*
