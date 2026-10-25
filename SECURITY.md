# Polityka Bezpieczeństwa (Security Policy) — WildAI Poland

W WildAI Poland bezpieczeństwo naszych użytkowników, ich kodu oraz danych systemowych jest najwyższym priorytetem. Niniejszy dokument opisuje procedurę zgłaszania oraz postępowania z potencjalnymi lukami w zabezpieczeniach.

---

## 🛡️ Wspierane wersje

Poniższa tabela przedstawia wspierane wersje poszczególnych komponentów ekosystemu:

| Projekt | Wersja | Wsparcie łatek bezpieczeństwa |
| :--- | :---: | :---: |
| **WildAI Chat v2** | `2.x` | ✅ Aktywne |
| **WildAI CLI** | `1.2.x` | ✅ Aktywne |
| **WildAI CLI** | `< 1.2` | ❌ Brak wsparcia (zalecana aktualizacja) |

---

## 🚨 Jak zgłaszać luki bezpieczeństwa (Responsible Disclosure)

**Prosimy NIE publikować publicznych issue na GitHubie dotyczących luk podatności do momentu ich załatania.**

Jeśli odkryłeś lukę bezpieczeństwa w którymkolwiek projekcie organizacji **WildAI Poland**:

1. Skontaktuj się bezpośrednio z zespołem bezpieczeństwa:
   - **Email:** `security@wildai.pl` lub `deloskiyt@gmail.com`
   - **Temat wiadomości:** `[SECURITY] Podatność w <nazwa_projektu>`
2. W zgłoszeniu prosimy zawrzeć:
   - Dokładny opis problemu (Proof of Concept, kroki do odtworzenia).
   - Ocenę wpływu podatności (np. wyciek danych, Remote Code Execution, Path Traversal, ominięcie autoryzacji).
   - Wersję oprogramowania oraz środowisko (system operacyjny, wersja Node.js).

---

## ⏱️ Harmonogram odpowiedzi

* **Potwierdzenie zgłoszenia:** do 48 godzin od momentu otrzymania wiadomości.
* **Wstępna weryfikacja i ocena ryzyka:** do 5 dni roboczych.
* **Publikacja poprawki (Patch):** zależnie od krytyczności, zazwyczaj od 2 do 14 dni.

Dziękujemy wszystkim badaczom i użytkownikom wspierającym bezpieczeństwo otwartego ekosystemu AI!
