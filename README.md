# Atak SQL Injection przy użyciu Kali Linux

## Opis

W ramach tego ćwiczenia przeprowadzimy atak SQL Injection na aplikację internetową, aby wykazać jej podatność na tego typu ataki. Wykorzystamy Kali Linux do wykonania ataku i narzędzie `sqlmap` do automatycznego wykrycia i wykorzystania podatności.

## Przygotowanie

1. **Uruchomienie Kali Linux:**
   - Uruchom maszynę wirtualną z zainstalowanym systemem Kali Linux.

2. **Zakładki Zdjęciowe:**
   - W poniższych sekcjach umieszcz zdjęcia z poszczególnymi krokami ataku:
     1. Zrzut ekranu potwierdzający dostępność strony internetowej w maszynie wirtualnej.
     2. Zrzut ekranu przeglądarki, gdzie widoczny będzie atak SQL Injection z wykorzystaniem odpowiedniego ładunku.
     3. Zrzut ekranu z konsoli Kali Linux, pokazujący informacje uzyskane za pomocą narzędzia `sqlmap`.
  
![Sprawdzenie Czy strona jest widoczna w przeglądarce](https://github.com/Kamilq99/sqlinjectionbykalilinux/assets/83961352/749afcf3-3c29-47dd-b713-89e183102d0b)
![Wykonanie ataku sqlinjection](https://github.com/Kamilq99/sqlinjectionbykalilinux/assets/83961352/9576de06-6a85-4e21-8a04-5a114615c4e3)
![Wylistowanie Wrażliwych na atak warstw bazy danych](https://github.com/Kamilq99/sqlinjectionbykalilinux/assets/83961352/9ff24318-5c2f-4a0d-9a11-3ce4e046342f)


## Atak SQL Injection

1. **Identyfikacja Podatnego URL:**
   - Przejrzyj stronę internetową w przeglądarce i zidentyfikuj podatny parametr URL, który jest podatny na ataki SQL Injection.

2. **Wykonanie Ataku:**
   - Wykorzystaj narzędzie `sqlmap` do przeprowadzenia ataku SQL Injection na identyfikowanym URL.
   - Zastosuj różne techniki ataku, takie jak boolean-based blind, time-based blind czy UNION query, aby zweryfikować podatność aplikacji.

3. **Analiza Wyników:**
   - Po przeprowadzeniu ataku, przeanalizuj wyniki uzyskane za pomocą `sqlmap` w celu zrozumienia, jakie informacje można wydobyć z bazy danych.
   - Zrób zrzut ekranu z konsoli Kali Linux, aby pokazać otrzymane wyniki, takie jak struktura bazy danych, tabele i zawartość kolumn.

