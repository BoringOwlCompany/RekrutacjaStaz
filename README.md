# RekrutacjaStaz

## Zadanie 1
0. Utwórz fork tego repozytorium u siebie na koncie github.
1. Wykorzystaj Create-React-App i utwórz projekt React.
2. Zainstaluj bibliotekę z gotowymi komponentami https://material-ui.com/
3. Stwórz Menu boczne które będzie wykorzystywało następujący obiekt:

```javascript
const menuItems = [
  {
    label: "Link1",
    link: "link1"
  },
  {
    label: "Link2",
    link: "link2"
  }
]
```

Obiekt nazwij jako MenuItemsContainer
Wykorzystaj dowolny sposób stylowania komponentów z dokumentacji materialui
Zainstaluj wybraną bibliotekę do routingu i podłącz routing do poszczególnych linków zawartych w menu items.

4. Utwórz Page Link1 oraz Page Link2. 

- Strona Link1 powinna zawierać dowolny tekst lorem ipsum. Tekst powinien mieć rozmiar 22px, bold, border 1px red.
- Strona Link2 powinna zawierać komponent switch

5. Wykorzystaj useState i podłącz do komponentu switch. Komponent switch powinien pokazywać i chować menu.
6. Strona Link2 dodatkowo powinna odpytać
7. Wykorzystaj API https://reqres.in/api/users?page=2 i pobierz użytkowników. Wyświetł ich listę na stronie głównej bez routingu w dowolny nieostylowany sposób.
8. Przetestuj dowolny stworzony przez siebie komponent
9* Wykorzystaj ContextAPI a także useState i utwórz globalny stan, który po wciśnięciu przycisku na stronie głównej ( button o nazwie POKAZ ), będzie pokazywał tekst "TEKST" w menu bocznym. Zimportuj context do menu bocznego wykorzystując useContext, a także podłącz zmianę stanu globalnego do przycisku.


Oceniane będzie:
- ilość wykonanych zadań
- commity
- umiejętność korzystania z dokumentacji i wykorzystania gotowych komponentów
- umiejętność przetestowania komponentu
- nie dokumentujemy komponentów, nazwa komponentów, funkcji powinna mówić sama za siebie
- wykorzystanie context api
- wszystkie komponenty mają wykorzystywać arrow functions, const fun = props => console.log(props.someProp)
