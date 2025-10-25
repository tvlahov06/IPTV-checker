# IPTV Checker Web App (Smart Proxy)

Ova verzija koristi automatski Smart Proxy sustav koji omogućuje rad i na GitHub Pagesu bez CORS grešaka.

## Logika dohvaćanja
1. Lokalno (file://, localhost) → izravni API poziv.
2. Online (GitHub Pages, HTTPS) → pokušava redom:
   - AllOrigins
   - corsproxy.io
   - ako oba padnu → prikaže link za ručni test.

## Ikone
Plave privremene ikone (favicon + PWA).

## Pokretanje
1. Otvorite `index.html` lokalno ili hostajte na GitHub Pages.
2. Unesite M3U link ili ručno podatke.
3. Kliknite **Provjeri pretplatu**.
