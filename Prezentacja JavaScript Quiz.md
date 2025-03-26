# Zadanie: Naprawa stylów CSS w quizie

## Opis zadania

Poniżej znajduje się kod CSS z **celowo wprowadzonymi błędami i nieprawidłowymi ustawieniami**.  
Twoim zadaniem jest odnaleźć i **naprawić style**, aby quiz wyglądał estetycznie, był czytelny i zgodny z zamysłem interfejsu z lekcji.  
Dodatkowo przy każdej grupie stylów znajdziesz **krótkie wyjaśnienie, do czego służą te właściwości CSS**.

---

## Instrukcje krok po kroku

### 1. **Reset stylów**

```css
.quiz-box {
  background: #fff;
  padding: 0px;              /* ❌ Popraw na np. 30px */
  border-radius: 0px;        /* ❌ Zaokrąglij np. 8px */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.9); /* ❗ Zbyt ciemny cień */
  max-width: 600px;
  width: 100%;
  text-align: right;         /* ❌ Popraw na center lub left */
}
```

```css
.quiz-box h2 {
  font-size: 8px; /* ❌ Zbyt mały tekst */
  margin-bottom: 20px;
}
```

```css
.answer-buttons li {
  margin: 0px 0; /* ❌ Dodaj odstęp między przyciskami */
}

.answer-buttons button {
  width: 100%;
  padding: 12px 20px;
  font-size: 16px;
  border: 2px solid #007bff;
  border-radius: 5px;
  background-color: white;
  color: #007bff;
  cursor: pointer;
  transition: 0.3s;
}
```

```css
.score {
  margin-top: 15px;
  font-weight: bold;
  color: #e3e3e3; /* ❌ Zbyt jasny – słabo widoczny na jasnym tle */
}
```

## Podsumowanie
🔍 Znalezione błędy:

- Zbyt małe fonty (h2, text-align: right)

- Brak marginesów między odpowiedziami

- Zbyt ciemny cień

- Zbyt jasny tekst wyniku

- Brak pełnych stylów w .parallax dla quizu i gry

## ✅ Zadanie dla Ciebie:

- Znajdź te fragmenty w kodzie CSS.

- Popraw style tak, aby quiz wyglądał estetycznie i był czytelny.

- Uruchom stronę w przeglądarce i sprawdź efekt!