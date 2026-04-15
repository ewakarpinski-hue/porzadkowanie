[README.md](https://github.com/user-attachments/files/26761690/README.md)
# PhotoSort AI • Offline

Automatyczne indeksowanie, tagowanie techniczne i wykrywanie duplikatów zdjęć. Aplikacja działa w 100% lokalnie, zapewniając pełną prywatność Twoich danych.

## Funkcje

- **🔍 Skanowanie i indeksowanie:** Szybkie przeszukiwanie dużych zbiorów zdjęć i zapisywanie metadanych technicznych.
- **🖼️ Galeria:** Przejrzysty podgląd Twojej biblioteki z informacjami o parametrach zdjęcia (ISO, aparat, wymiary).
- **📊 Statystyki:** Analiza zbiorów zdjęć wg folderów, aparatów oraz osi czasu.
- **🔍 Wykrywanie podobieństw:** Znajdowanie wizualnych duplikatów przy użyciu algorytmu *Perceptual Hashing*.
- **📤 Inteligentny eksport:** Automatyczne porządkowanie zdjęć do nowej struktury folderów wg daty, typu pliku lub modelu aparatu.

## Instalacja

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/ewakarpinski-hue/porzadkowanie.git
   cd porzadkowanie
   ```

2. Zainstaluj wymagane biblioteki:
   ```bash
   pip install -r requirements.txt
   ```

3. Uruchom aplikację:
   ```bash
   streamlit run app.py
   ```

## Technologie

- **Python** & **Streamlit** (UI)
- **SQLite** (Baza danych metadanych)
- **Pillow** (EXIF & Image processing)
- **ImageHash** (Podobieństwo obrazów)
- **Pandas** (Analiza danych)

---
*Created with ❤️ by PhotoSort AI*
