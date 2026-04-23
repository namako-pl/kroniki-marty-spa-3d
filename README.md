# Kroniki Marty - Interactive Wellness Platform

## Project Overview
A modern Single Page Application (SPA) designed to provide an immersive user experience through advanced WebGL technologies.

## 🌌 Akasha Records Portal – Immersive Web Experience

An interactive, high-performance landing page created for an Akasha Records consultant. The project combines mystical aesthetics with advanced frontend technologies like WebGL and creative animations.

![Project Preview](preview.jpg)

## ✨ Features

- **Interactive WebGL Field:** A custom particle system (The "Quantum Field") built with **Three.js** that reacts to mouse movement (desktop) and touch events (mobile).
- **Responsive Creative Design:** Modern UI utilizing **Glassmorphism** effects, custom CSS Grids, and a mobile-first approach.
- **Adaptive Performance:** Smart resource management that adjusts the particle count (4,000 for mobile vs. 8,000 for desktop) to maintain 60 FPS and save battery on mobile devices.
- **Instant Telegram Notifications:** A custom **PHP backend** integrated with the **Telegram Bot API**. Inquiries from the contact form are delivered instantly to the client’s messenger.
- **Smooth SPA Navigation:** Intelligent ScrollSpy using the **Intersection Observer API**, which updates the URL hash dynamically without page refreshes.

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3 (Grid & Flexbox), JavaScript (ES6+).
- **Creative Coding:** [Three.js](https://threejs.org/) (WebGL engine), [GSAP](https://greensock.com/gsap/) (Animations & ScrollTrigger).
- **Backend:** PHP (Form handling & Telegram API Bridge).

## 🚀 Technical Deep Dive

### 1. Quantum Field & WebGL Optimization
The background is not a video; it's a real-time rendered 3D scene. 
- I used `THREE.BufferGeometry` to minimize memory overhead. 
- The interaction logic includes `touchmove` event listeners, allowing mobile users to "touch the energy" just like desktop users.
- To ensure performance, I implemented a conditional particle count based on the user's device width.

### 2. URL Management & UX
To solve the issue of sticky URL hashes (like `#kontakt` staying in the bar when scrolling up):
- I implemented a script using the **Intersection Observer API** to track the user's position.
- When the user returns to the top, the script uses `history.replaceState` to clean the URL, providing a premium feel to the navigation.

### 3. Telegram Integration
Instead of relying on often-delayed SMTP emails, I built a PHP bridge to the **Telegram Bot API**. This ensures:
- 0-latency delivery of client inquiries.
- Enhanced reliability (bypassing spam filters).
- Instant notifications directly on the consultant's mobile phone.

- ## 👤 Author
**Natalia Kowalska (Namako)**
- Website: [namako.eu](http://namako.eu)
- LinkedIn: [Natalia Kowalska](https://www.linkedin.com/in/namako/)

  

## Polska wersja

# 🌌 Portal Kronik Akaszy – Immersyjne Doświadczenie Webowe

Interaktywna, wysokowydajna strona typu landing page stworzona dla konsultantki Kronik Akaszy. Projekt łączy mistyczną estetykę z nowoczesnymi technologiami frontendowymi, takimi jak WebGL, w celu wizualizacji „Kwantowego Pola Informacyjnego”.

![Podgląd Projektu](preview.png)

## ✨ Główne Funkcje

- **Interaktywne Tło WebGL:** Autorski system cząsteczek („Pole Kwantowe”) zbudowany w **Three.js**, który dynamicznie reaguje na ruch myszy (desktop) oraz zdarzenia dotykowe (mobile).
- **Adaptacyjna Wydajność:** Inteligentne zarządzanie zasobami – system automatycznie dostosowuje liczbę cząsteczek (4 000 dla urządzeń mobilnych vs. 8 000 dla desktopów), aby utrzymać 60 FPS i oszczędzać baterię na telefonach.
- **Błyskawiczne Powiadomienia Telegram:** Autorski backend w **PHP** zintegrowany z **Telegram Bot API**. Zapytania z formularza kontaktowego są przesyłane natychmiastowo bezpośrednio do komunikatora klientki.
- **Płynna Nawigacja SPA:** Inteligentny mechanizm ScrollSpy oparty na **Intersection Observer API**, który dynamicznie aktualizuje adres URL (hash) bez przeładowywania strony.
- **Nowoczesny UI:** Estetyka oparta na trendzie **Glassmorphism**, wykorzystująca zaawansowane układy CSS Grid i Flexbox.

## 🛠 Stos Technologiczny

- **Frontend:** HTML5, CSS3 (Grid & Flexbox), JavaScript (ES6+).
- **Creative Coding:** [Three.js](https://threejs.org/) (silnik WebGL), [GSAP](https://greensock.com/gsap/) (animacje i ScrollTrigger).
- **Backend:** PHP (Integracja z API Telegrama).
- **Optymalizacja:** Podejście Mobile-first i dbałość o wydajność renderowania.

## 🚀 Analiza Techniczna

### 1. Optymalizacja Pola WebGL
Tło strony nie jest statycznym filmem, lecz sceną 3D renderowaną w czasie rzeczywistym. 
- Wykorzystałam `THREE.BufferGeometry`, aby zminimalizować zużycie pamięci operacyjnej.
- Implementacja obejmuje obsługę zdarzeń `touchmove`, co pozwala użytkownikom mobilnym na interakcję z „energią” strony w taki sam sposób, jak na komputerach stacjonarnych.

### 2. Zarządzanie Adresami URL i UX
Aby rozwiązać problem „zostających” końcówek URL (np. `#kontakt` widoczny w pasku adresu po powrocie na górę strony):
- Wdrożyłam skrypt monitorujący pozycję użytkownika za pomocą **Intersection Observer API**.
- Gdy użytkownik wraca do sekcji powitalnej, skrypt używa `history.replaceState`, aby wyczyścić adres URL, co nadaje nawigacji luksusowy charakter (tzw. premium feel).

### 3. Integracja z Telegramem (Security & Speed)
Zamiast polegać na tradycyjnym e-mailu (który często trafia do spamu), stworzyłam most (bridge) w PHP do API Telegrama. Zapewnia to:
- Zerowe opóźnienie w dostarczaniu zapytań od klientów.
- Większą niezawodność i bezpieczeństwo danych.
- Natychmiastowe powiadomienia push na telefonie klientki.

## 👤 Autorka
**Natalia Kowalska (Namako)**
- Strona www: [namako.eu](http://namako.eu)
- LinkedIn: [Natalia Kowalska](https://www.linkedin.com/in/namako/)

---
*Projekt stworzony z pasją do łączenia wizualnego storytellingu z wysoką wydajnością rozwiązań frontendowych.*
