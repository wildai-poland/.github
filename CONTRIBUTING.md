# Wytyczne dla Twórców (Contributing Guide) — WildAI Poland

Dziękujemy za zainteresowanie rozwojem ekosystemu **WildAI Poland**! Każdy wkład — od poprawiania literówek po wdrażanie zaawansowanych silników agentowych — jest mile widziany.

---

## 🛠️ Jak zacząć

1. **Fork i Clone:**
   Sforkuj repozytorium projektu, a następnie sklonuj je lokalnie:
   ```bash
   git clone https://github.com/<twoj-login>/<projekt>.git
   cd <projekt>
   ```

2. **Gałęzie (Branching):**
   Twórz tematyczne gałęzie z opisową nazwą:
   ```bash
   git checkout -b feat/dodanie-nowego-modelu
   # lub
   git checkout -b fix/naprawa-strumieniowania
   ```

3. **Standardy kodu:**
   - Pisz czytelny kod w języku TypeScript.
   - Upewnij się, że projekt buduje się bez błędów (`npm run build`).
   - Zadbaj o formatowanie i brak nieużywanych zmiennych.
   - Pamiętaj o zasadach bezpieczeństwa — nigdy nie commituj kluczy API ani tokenów (`.env`).

4. **Konwencja commitów (Conventional Commits):**
   Używamy standardu Semantic Commit Messages:
   - `feat:` nowa funkcja
   - `fix:` poprawka błędu
   - `docs:` zmiany w dokumentacji
   - `refactor:` refaktoryzacja kodu bez zmiany zachowania
   - `perf:` optymalizacja wydajności

5. **Pull Request (PR):**
   - Wypchnij gałąź do swojego forka i utwórz Pull Request do gałęzi `main`.
   - Opisz dokładnie cel zmian oraz dodaj zrzuty ekranu, jeśli zmiana dotyczy interfejsu użytkownika.
