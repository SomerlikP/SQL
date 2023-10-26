# Resetowanie ID:
1. ALTER TABLE nazwaTablei MODIFY COLUMN id INT NOT NULL;
2. SET @counter = 0; UPDATE nazwaTabeli SET id = (@counter:=@counter+1);
3. ALTER TABLE nazwaTablei MODIFY COLUMN id INT NOT NULL AUTO_INCREMENT; <br><br>


# SELECT - Wybierz: służy do wybierania kolumn, które mają zostać zwrócone w wyniku zapytania. <br><br>

# FROM - Z: określa tabelę źródłową, z której mają zostać zwrócone dane. <br><br>

# UPDATE - Aktualizuj: służy do modyfikowania istniejących rekordów w tabeli. <br><br>

# WHERE - Gdzie: umożliwia filtrowanie wyników zapytania według określonych kryteriów. <br><br>

# BETWEEN - Pomiędzy: służy do filtrowania wyników w określonym zakresie wartości. <br><br>

# AND - I: operator logiczny łączący dwa warunki; oba warunki muszą być spełnione. <br><br>

# OR - Lub: operator logiczny łączący dwa warunki; co najmniej jeden z warunków musi być spełniony. <br><br>

# DESC - Malejąco: służy do sortowania wyników w kolejności malejącej. <br><br>

# ASC - Rosnąco: służy do sortowania wyników w kolejności rosnącej (domyślnie). <br><br>

# AVG - Średnia: funkcja agregująca, która zwraca średnią wartość określonej kolumny. <br><br>

# SUM - Suma: funkcja agregująca, która zwraca sumę wartości określonej kolumny. <br><br>

# COUNT - Liczba: funkcja agregująca, która zwraca liczbę wierszy spełniających określone kryteria. <br><br>

# MIN - Minimum: funkcja agregująca, która zwraca najmniejszą wartość określonej kolumny. <br><br>

# MAX - Maksimum: funkcja agregująca, która zwraca największą wartość określonej kolumny. <br><br>

# GROUP BY - Grupuj według: klauzula używana do grupowania wierszy, które mają takie same wartości w określonych kolumnach. <br><br>

# ORDER BY - Sortuj według: klauzula używana do sortowania wyników według określonych kolumn. <br><br>

# INSERT INTO - Wstaw do: służy do dodawania nowych rekordów do tabeli. <br><br>

# DELETE - Usuń: służy do usuwania rekordów z tabeli. <br><br>

# JOIN - Dołącz: używane do łączenia wierszy z dwóch lub więcej tabel, opartych na wspólnej kolumnie. <br><br>

# INNER JOIN - Wewnętrzne dołączenie: zwraca wiersze, gdy istnieje przynajmniej jedno pasujące wiersze w obu tabelach. <br><br>

# LEFT JOIN (lub LEFT OUTER JOIN) - Lewe dołączenie: zwraca wszystkie wiersze z lewej tabeli oraz pasujące wiersze z prawej tabeli. <br><br>

# RIGHT JOIN (lub RIGHT OUTER JOIN) - Prawe dołączenie: zwraca wszystkie wiersze z prawej tabeli oraz pasujące wiersze z lewej tabeli. <br><br>

# FULL JOIN (lub FULL OUTER JOIN) - Pełne dołączenie: zwraca wiersze, gdy istnieje pasujący wiersz w jednej z tabel. <br><br>

# DISTINCT - Unikalne: służy do zwracania unikalnych wartości w wynikach zapytania. <br><br>

# LIKE - Jak: używane w klauzuli WHERE do wyszukiwania określonego wzorca w kolumnie. <br><br>

# IN - W: pozwala określić wiele wartości w klauzuli WHERE. <br><br>

# NOT - Nie: używane w klauzuli WHERE do negowania następującego po nim warunku. <br><br>

# IS NULL - Jest NULL: filtruje kolumny, które mają wartość NULL. <br><br>

# IS NOT NULL - Nie jest NULL: filtruje kolumny, które nie mają wartości NULL. <br><br>

# ALTER TABLE - Modyfikuj tabelę: służy do dodawania, usuwania lub modyfikowania kolumn w istniejącej tabeli. <br><br>

# CREATE TABLE - Utwórz tabelę: służy do tworzenia nowej tabeli. <br><br>

# DROP TABLE - Usuń tabelę: służy do usuwania tabeli. <br><br>

# CREATE INDEX - Utwórz indeks: służy do tworzenia indeksu na jednej lub wielu kolumnach. <br><br>

# DROP INDEX - Usuń indeks: służy do usuwania indeksu. <br><br>

# CREATE DATABASE - Utwórz bazę danych: służy do tworzenia nowej bazy danych. <br><br>

# DROP DATABASE - Usuń bazę danych: służy do usuwania bazy danych. <br><br>

# UNION - Unia: służy do łączenia wyników dwóch zapytań SELECT (bez duplikatów). <br><br>

# UNION ALL - Cała unia: służy do łączenia wyników dwóch zapytań SELECT (z duplikatami). <br><br>

# CASE - Przypadek: służy do tworzenia wyrażeń warunkowych w zapytaniach. <br><br>

# HAVING - Mając: filtruje wyniki funkcji agregujących, podobnie jak klauzula WHERE dla indywidualnych wierszy. <br><br>

# EXISTS - Istnieje: testuje istnienie wierszy w podzapytaniu. <br><br>

# LIMIT - Limit: ogranicza liczbę zwracanych wierszy. <br><br>

# OFFSET - Przesunięcie: określa, od którego wiersza zaczynać zwracanie wyników. <br><br>

# CHARACTER SET - Zestaw znaków: określa zestaw znaków dla tabeli lub kolumny. <br><br>

# COLLATE - Porządek sortowania: określa porządek sortowania dla tabeli lub kolumny. <br><br>

# PRIMARY KEY - Klucz główny: unikalny identyfikator dla rekordu w tabeli. <br><br>

# FOREIGN KEY - Klucz obcy: klucz używany do łączenia wierszy z innej tabeli. <br><br>

# CHECK - Sprawdź: określa warunek, który musi spełniać każda wartość w kolumnie. <br><br>

# DEFAULT - Domyślna: wartość, która jest ustawiana dla kolumny, gdy nie jest podawana żadna inna wartość. <br><br>

# INDEX - Indeks: używany do przyspieszania zapytań. <br><br>

# AUTO_INCREMENT - Autoinkrementacja: pozwala na automatyczne zwiększanie wartości dla kolumny (często używane z kluczem głównym). <br><br>

# DATE - Data: funkcja lub typ danych używany do reprezentowania dat. <br><br>

# TIMESTAMP - Znacznik czasu: typ danych reprezentujący datę i czas. <br><br>

# SUBSTRING - Podciąg: funkcja używana do wyciągania części ciągu znaków. <br><br>

# UPPER - Wielkie litery: konwertuje ciąg na wielkie litery. <br><br>

# LOWER - Małe litery: konwertuje ciąg na małe litery. <br><br>

# TRIM - Usuń białe znaki: usuwa białe znaki z początku i końca ciągu. <br><br>

# LENGTH - Długość: zwraca długość ciągu znaków. <br><br>

# ROUND - Zaokrąglenie: funkcja matematyczna do zaokrąglania liczb. <br><br>

# CAST - Rzutowanie: konwertuje jedno dane na inny typ danych. <br><br>

# COALESCE - Koalescencja: zwraca pierwszą nie-nullową wartość w liście. <br><br>

# NULLIF - Jeśli null: zwraca null, jeśli dwie wartości są równe; w przeciwnym razie zwraca pierwszą wartość. <br><br>

# OUTER APPLY i CROSS APPLY - stosowane głównie w SQL Server, służą do łączenia tabeli z wynikami funkcji tablicowej. <br><br>

# CTE (Common Table Expressions) - Wspólne wyrażenia tabelaryczne: używane do definiowania tymczasowych wyników, które można następnie odwoływać w głównym zapytaniu. <br><br>

# WITH - Z: używane z CTE do definiowania tymczasowych wyników. <br><br>

# PIVOT - Pivot: służy do transformacji danych z formatu wierszowego na format kolumnowy. <br><br>

# UNPIVOT - Unpivot: służy do przekształcania danych z formatu kolumnowego na format wierszowy. <br><br>

# ROW_NUMBER(), RANK(), DENSE_RANK(), NTILE() - funkcje okienne służące do przypisywania wartości w oparciu o porządek wierszy. <br><br>

# OVER - Nad: klauzula używana z funkcjami okiennymi do określenia zakresu wierszy, na których ma działać funkcja. <br><br>

<br><br><br>

# USELESS:

# OFFSET - Przesunięcie: określa, od którego wiersza zaczynać zwracanie wyników. <br><br>

# CHARACTER SET - Zestaw znaków: określa zestaw znaków dla tabeli lub kolumny. <br><br>

# COLLATE - Porządek sortowania: określa porządek sortowania dla tabeli lub kolumny. <br><br>

# DEFAULT - Domyślna: wartość, która jest ustawiana dla kolumny, gdy nie jest podawana żadna inna wartość. <br><br>

# SUBSTRING - Podciąg: funkcja używana do wyciągania części ciągu znaków. <br><br>

# CAST - Rzutowanie: konwertuje jedno dane na inny typ danych. <br><br>

# NULLIF - Jeśli null: zwraca null, jeśli dwie wartości są równe; w przeciwnym razie zwraca pierwszą wartość. <br><br>

# OUTER APPLY i CROSS APPLY - stosowane głównie w SQL Server, służą do łączenia tabeli z wynikami funkcji tablicowej. <br><br>

# CTE (Common Table Expressions) - Wspólne wyrażenia tabelaryczne: używane do definiowania tymczasowych wyników, które można następnie odwoływać w głównym zapytaniu. <br><br>

# PIVOT - Pivot: służy do transformacji danych z formatu wierszowego na format kolumnowy. <br><br>

# UNPIVOT - Unpivot: służy do przekształcania danych z formatu kolumnowego na format wierszowy. <br><br>

# ROW_NUMBER(), RANK(), DENSE_RANK(), NTILE() - funkcje okienne służące do przypisywania wartości w oparciu o porządek wierszy. <br><br>

# OVER - Nad: klauzula używana z funkcjami okiennymi do określenia zakresu wierszy, na których ma działać funkcja. <br><br>
