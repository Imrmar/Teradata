# Tables 
### Derived table
  Derived table je derivovaná tabule z existující tabule. Jedná se prakticky o subselect, technicky je to vlastně něco jako view.
  Select * from
  (Select name, surname from employee) as Derived_Employee
  
### Volatile table
  Volatile table je volatilní tabulka, která se při ukončení sesiony dropne.
  CREATE VOLATILE TABLE
  
### Temporal table
  Temporal table je tabulka, která má uloženou strukturu v databázi, ale po ukončení sessiony se promaže a demateralizuje.
  CREATE SET GLOBAL TEMPORARY TABLE 
  
# Space
### Permanent space
  Maximální možné místo pevně dedikované určité databázi/uživateli.

### Spool space
  Dočasně zabrané místo nějakou běžící query.
  
### Temp Space
  Temp space je nevyužitá část permanent space, kterou momentálně využívají temporální tabulky.
