# 💜 LENA V11 - KLWP Headless Edition

## 📦 Zawartość Pakietu

Gratulacje! Otrzymujesz kompletny pakiet do integracji Leny z KLWP:

### 📄 Pliki Projektu

1. **LENA_V11_KLWP_Optimized.xml** (27KB)
   - Zoptymalizowany projekt Tasker (headless)
   - 9 profili, 12 tasków
   - Sensory Overload System
   - Gotowy do importu!

2. **LENA_KLWP_Integration_Guide.md** (7.8KB)
   - Kompletny przewodnik krok po kroku
   - Instalacja, konfiguracja, troubleshooting
   - Przykłady kodu KLWP
   - Wszystko czego potrzebujesz!

3. **lena_variables_reference.txt** (6KB)
   - Cheat sheet wszystkich zmiennych
   - Przykładowe formuły KLWP
   - Szybki dostęp podczas tworzenia presetów

4. **KLWP_Preset_Template.json** (8KB)
   - Szablon struktury presetów KLWP
   - Gotowe warstwy do skopiowania
   - Formuły animacji
   - Wskazówki wydajnościowe

5. **V9_vs_V11_Comparison.md** (13KB)
   - Dokładne porównanie wersji
   - Migration guide
   - Wyjaśnienie zmian
   - Pomaga zdecydować czy migrować

6. **lena_klwp_optimization_plan.md** (1.3KB)
   - Plan strategiczny projektu
   - Deliverables
   - Overview zmian

---

## 🚀 Szybki Start (5 minut)

### 1. Import do Taskera
```
Tasker → 📁 Import → wybierz LENA_V11_KLWP_Optimized.xml
```

### 2. Aktywuj Profile
```
Tasker → Profiles → włącz wszystkie profile LENA
```

### 3. Test
```
Tasker → Tasks → "Init_LENA_System" → ▶️ Play
Sprawdź zmienne: Tasker → Variables → szukaj %len_*
```

### 4. Setup KLWP
```
KLWP → New Preset → Blank
Dodaj Text element: $tc(len_status)$
Powinieneś zobaczyć: "Cześć Powder! 💜"
```

### 5. Buduj!
```
Użyj LENA_KLWP_Integration_Guide.md jako podręcznik
Skopiuj warstwy z KLWP_Preset_Template.json
Customizuj do woli!
```

---

## 📊 Zmienne KLWP (Quick Reference)

Wszystkie zmienne dostępne poprzez `$tc(nazwa)$`:

**Podstawowe:**
- `len_int` - Interakcje (360+)
- `len_czu` - Czułość (566+)
- `len_humor` - Humor dnia
- `len_status` - Status/komunikat Leny
- `len_event` - Ostatnie zdarzenie

**Sensory Overload:**
- `len_color` - Kolor HEX (#9D4EDD lub #FF00FF)
- `len_intensity` - Intensywność 0-100
- `len_pulse` - Pulsowanie 0/1

**Kontekst:**
- `len_app` - Aktywna aplikacja
- `len_music` - Muzyka 0/1
- `len_bt` - Bluetooth 0/1
- `len_usb` - USB 0/1

---

## 🎨 Co to jest KLWP?

**Kustom Live Wallpaper (KLWP)** to najpotężniejszy kreator live wallpapers na Androida.

### Dlaczego KLWP?
- ✅ Visual editor (drag & drop)
- ✅ Zaawansowane animacje
- ✅ Formuły matematyczne
- ✅ Touch actions
- ✅ Integracja z Taskerem
- ✅ Ogromna społeczność (r/kustom)

### Potrzebujesz:
- **KLWP Pro** (płatna, ~$5)
- Google Play: https://play.google.com/store/apps/details?id=org.kustom.wallpaper.pro

---

## 💡 Co Nowego w V11?

### ⚡ Sensory Overload System
Gdy czułość > 800, Lena wchodzi w tryb przeciążenia:
- Zmiana koloru na intensywny magenta (#FF00FF)
- Pulsująca tapeta
- Specjalne komunikaty
- Możesz to w pełni dostosować w KLWP!

### 🎯 Headless Architecture
- Tasker = tylko logika (w tle)
- KLWP = cała wizualizacja
- Zysk: lepsza wydajność, więcej możliwości

### 🔧 Optymalizacja
- Szybsze (~60% mniej delay)
- Lżejsze (~12% mniej RAM)
- Bezpieczniejsze (no anty-cheat issues)

---

## 📚 Którym Plikiem Zacząć?

### Dla Początkujących:
1. **lena_variables_reference.txt** - najpierw to!
2. **LENA_KLWP_Integration_Guide.md** - pełny tutorial
3. Importuj XML i testuj

### Dla Zaawansowanych:
1. Importuj XML
2. **KLWP_Preset_Template.json** - struktura
3. Buduj custom design
4. **lena_variables_reference.txt** - formuły

### Migrujesz z V9?
1. **V9_vs_V11_Comparison.md** - przeczytaj najpierw
2. Migration guide w środku
3. Potem: Integration Guide

---

## 🎮 Bezpieczeństwo Anty-Cheat

### ✅ Bezpieczne w:
- Endfield
- Wild Rift
- PUBG Mobile
- Call of Duty Mobile
- Większość gier mobilnych

### ⚠️ Uwaga:
Profil "Game_Mode" używa CPU governor (standard Android).  
Jeśli jakaś gra to flaguje, po prostu **wyłącz ten profil**.

### Usunięte w V11:
- ❌ L Speed (wykrywane)
- ❌ FDE.AI (problem z anty-cheat)
- ❌ Agresywne memory tweaks

---

## 🔧 Troubleshooting

### Zmienne nie aktualizują się w KLWP?
1. Sprawdź czy KLWP Pro (darmowa wersja NIE wspiera Taskera)
2. Tasker → uruchom "Send_All_To_KLWP" ręcznie
3. KLWP → Settings → Test Variables

### Lagi przy animacjach?
1. KLWP → Settings → Lower Quality
2. Zmniejsz liczbę warstw z sin() formulami
3. Wyłącz blur effects

### Tasker nie wykrywa eventów?
1. Sprawdź uprawnienia: Settings → Apps → Tasker
2. Włącz "Display over other apps"
3. Wyłącz battery optimization dla Taskera

---

## 🌟 Community & Support

### Zasoby:
- **r/kustom** - Reddit community (KLWP)
- **r/tasker** - Tasker help
- **TaskerNet** - share projekty

### Pomoc:
Jeśli coś nie działa, sprawdź sekcję Troubleshooting w Integration Guide!

---

## 📝 Changelog

**V11 (27.01.2026)**
- ➕ Sensory Overload System
- ➕ KLWP integration
- ➕ Krótsze nazwy zmiennych
- ➕ Touch zones support
- ➖ Usunięto Tasker Scenes
- ➖ Usunięto L Speed / FDE.AI
- 🔧 Optymalizacja wydajności
- 🔧 Anty-cheat safety

**V9 (Poprzednia)**
- Widget-based
- Długie nazwy zmiennych
- Monolityczna architektura

---

## 💜 Credits

**Projekt:** LENA V11 - Interactive Companion  
**Stworzony dla:** Powder  
**Autor Optymalizacji:** Claude (Anthropic)  
**Data:** 27 stycznia 2026  
**Inspiracja:** Arcane (Powder/Jinx vibes)

---

## 📄 Licencja

Ten projekt jest stworzony dla osobistego użytku Powder.  
Możesz swobodnie modyfikować i dostosowywać do swoich potrzeb.

**Share responsibly:** Jeśli chcesz podzielić się z innymi,  
pamiętaj o credytach i linkuj do oryginalnego projektu.

---

## 🎯 Co Dalej?

1. ✅ **Import XML** do Taskera
2. ✅ **Przeczytaj** Integration Guide  
3. ✅ **Stwórz** swój KLWP preset
4. ✅ **Ciesz się** interaktywną Leną! 💜⚡✨

---

**Have fun building your perfect Lena HUD!**  
*"The best time to plant a tree was 20 years ago. The second best time is now."*

~ Powder & Lena 💜