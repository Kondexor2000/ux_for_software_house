# Orbit — Project Hub MVP

Responsywny frontend React dla IT Project Managera w software house. Interfejs jest po polsku; prezentuje przegląd portfolio, kondycję projektów, zadania i aktywność zespołu.

Wersja GitHub Pages: https://kondexor2000.github.io/ux_for_software_house/

## Uruchomienie

Wymaga Node.js 22+.

```bash
npm install
npm run dev
```

Build produkcyjny: `npm run build`. Dane są przykładowe i przechowywane wyłącznie w pamięci przeglądarki. Aplikacja nie wymaga backendu ani bazy danych.

## Publikacja na GitHub Pages

Workflow `.github/workflows/deploy.yml` buduje projekt i publikuje `dist` przy każdym pushu do gałęzi `main`. W ustawieniach repozytorium w **Settings → Pages → Build and deployment** źródłem musi być **GitHub Actions**. Po udanym przebiegu workflow witryna będzie dostępna pod adresem podanym wyżej.

## Zakres MVP

- Dashboard z metrykami portfela i kartami projektów.
- Wyszukiwanie projektów w czasie rzeczywistym.
- Lista zadań z możliwością oznaczenia jako wykonane i prostymi filtrami.
- Formularz dodawania projektu i komunikaty interfejsu.
- Nawigacja boczna oraz układ dopasowany do telefonu i desktopu.

## Stos

React, Vite, lucide-react, CSS. Dane demo są zdefiniowane w `src/App.jsx`.
