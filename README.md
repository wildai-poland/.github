<div align="center">

# 🌲 WildAI Poland

**Nowoczesny, niezależny i bezpieczny ekosystem sztucznej inteligencji.**  
*Budujemy polskie narzędzia AI nowej generacji: od webowego czatu po autonomiczne agenty terminalowe.*

[![Website](https://img.shields.io/badge/Web-v2.wildai.pl-10a37f?style=for-the-badge&logo=google-chrome&logoColor=white)](https://v2.wildai.pl)
[![Organization](https://img.shields.io/badge/Org-wildai--poland-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wildai-poland)
[![Status](https://img.shields.io/badge/Status-Aktywny%20Rozwój-emerald?style=for-the-badge)](https://v2.wildai.pl)
[![License](https://img.shields.io/badge/Licencja-MIT-blue?style=for-the-badge)](LICENSE)

<br/>

```ascii
  _       ___ __    _____   ____  ____  __    ___    _   ______ 
 | |     / (_) /___/ /   | /  _/ / __ \/ /   /   |  / | / / __ \
 | | /| / / / / __  / /| | / /  / /_/ / /   / /| | /  |/ / / / /
 | |/ |/ / / / /_/ / ___ |_/ /  / ____/ /___/ ___ |/ /|  / /_/ / 
 |__/|__/_/_/\__,_/_/  |_/___/ /_/   /_____/_/  |_/_/ |_/_____/  
```

</div>

---

### 🚀 O organizacji WildAI Poland

**WildAI Poland** to polska organizacja technologiczna, której celem jest dostarczenie programistom, twórcom i entuzjastom technologii wolnego od zbędnych ograniczeń, szybkiego oraz bezpiecznego środowiska do pracy z modelami LLM najnowszej generacji.

Rozwijamy kompletny ekosystem:
* 🌐 **Interfejsy webowe** — minimalistyczne, błyskawiczne aplikacje czatu w stylistyce ChatGPT 2026.
* 💻 **Narzędzia CLI & Agenty** — terminalowe środowiska pracy z autonomicznym agentem kodującym bezpośrednio na Twoim dysku.
* 🛡️ **Architektura bezpieczeństwa** — autorskie mechanizmy obrony przed Prompt Injection, szyfrowanie tokenów w macOS Keychain / AES-256-GCM oraz podejście Human-in-the-Loop.

---

### 📦 Kluczowe Projekty w Ekosystemie

<table>
  <thead>
    <tr>
      <th width="30%">Projekt</th>
      <th width="50%">Opis</th>
      <th width="20%">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://v2.wildai.pl"><b>💬 WildAI Chat v2</b></a>
      </td>
      <td>
        Nowoczesny webowy klient czatu AI. Posiada obsługę modeli bez cenzury (DeepSeek v4.1 Flash Uncensored), streaming SSE w czasie rzeczywistym, autorski system limitów dziennych zintegrowany z Neon PostgreSQL, pamięć wybranego modelu per czat oraz moduł awatarów użytkownika.
      </td>
      <td>
        <code>v2.0 (Produkcja)</code>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/deloskiytbackup/wildai-cli"><b>⚡ WildAI CLI</b></a>
      </td>
      <td>
        Oficjalny terminalowy asystent deweloperski z autonomicznym trybem agenta (Autonomous Developer Agent). Potrafi odczytywać kod, tworzyć pliki na dysku, weryfikować status Git i wykonywać testy z pełną kontrolą użytkownika.
      </td>
      <td>
        <code>v1.2 (Stabilna)</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>🛡️ WildAI Security Engine</b>
      </td>
      <td>
        Zestaw zabezpieczeń infrastruktury: sprzętowy zapis poświadczeń w macOS Keychain / AES-256-GCM, restrykcyjna ochrona Path Traversal oraz czarna lista destrukcyjnych poleceń powłoki.
      </td>
      <td>
        <code>Wbudowany</code>
      </td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Stos Technologiczny

<div align="center">

| Kategoria | Technologie |
| :--- | :--- |
| **Frontend & UI** | Next.js 16 (App Router, Turbopack), React 19, Tailwind CSS, Lucide Icons |
| **Backend & API** | Node.js, TypeScript, Next.js Route Handlers, Axios |
| **Baza Danych & ORM** | PostgreSQL (Neon Serverless), Prisma ORM v6 |
| **Silniki AI** | DeepSeek (R1, v4.1 Uncensored), Qwen 3.8, Claude Opus/Sonnet, Ollama |
| **Bezpieczeństwo** | macOS Keychain Access, AES-256-GCM, Human-in-the-Loop validation |

</div>

---

### ⚡ Szybki Start

#### 1. WildAI w Przeglądarce
Odwiedź oficjalną instancję: **[v2.wildai.pl](https://v2.wildai.pl)**  
Zarejestruj się lub korzystaj w trybie gościa z natychmiastowym dostępem do modeli.

#### 2. WildAI w Terminalu (CLI)
```bash
# Sklonuj repozytorium CLI
git clone https://github.com/wildai-poland/wildai-cli.git
cd wildai-cli

# Zainstaluj zależności i zbuduj
npm install
npm run build

# Uruchom asystenta
npm run dev

# Aby aktywować tryb agenta w terminalu wpisz:
/mode
```

---

### 🛡️ Bezpieczeństwo i Prywatność

W projektach organizacji **WildAI Poland** priorytetem jest ochrona użytkownika:
* **Zero nieautoryzowanego zapisu:** Żadne narzędzie agenta nie wykona modyfikacji Twojego pliku ani komendy bez wyraźnej zgody w terminalu.
* **Ochrona tokenów:** Tokeny autoryzacyjne są chronione w bezpiecznym magazynie systemowym (macOS Keychain lub pliki z uprawnieniami `0600`).
* **Zgłaszanie luk:** Jeśli zauważyłeś podatność w którymkolwiek z projektów, zapoznaj się z naszym [SECURITY.md](SECURITY.md).

---

### 🤝 Współpraca (Contributing)

Jesteśmy otwarci na pull requesty, pomysły na nowe funkcje oraz zgłoszenia błędów!
1. Zapoznaj się z [CONTRIBUTING.md](CONTRIBUTING.md).
2. Sprawdź zakładkę [Issues](https://github.com/wildai-poland/.github/issues) lub załóż nowe zgłoszenie.
3. Przestrzegaj zasad zawartych w [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

---

<div align="center">
  <sub>Stworzone z pasją w Polsce 🇵🇱 dla globalnej społeczności open-source.</sub><br/>
  <sub>© 2026 <b>WildAI Poland</b>. Wszystkie prawa zastrzeżone.</sub>
</div>
