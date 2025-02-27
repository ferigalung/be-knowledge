# DDL (Data Definition Language)
script untuk membuat struktur database.
contoh:
- CREATE
- ALTER
- DROP
- TRUNCATE
- COMMENT
- RENAME

# DML (Data Manipulation Language)
script untuk memanipulasi data di dalam database.
contoh:
- INSERT
- UPDATE
- DELETE
- SELECT

## Aggregate Function
function yang digunakan untuk melakukan operasi matematika pada data.
contoh:
- COUNT
- SUM
- AVG
- MAX
- MIN

## Scalar Function
beroperasi pada setiap baris data dan mengembalikan nilai tunggal.
kategori:
- Character
    - CONCAT
    - SUBSTR
    - INSTR
    - LENGTH
    - TRIM
    - REPLACE
    - LPAD
    - RPAD
    - LOWER
    - UPPER
    - INITCAP
    - REVERSE
    - TRANSLATE
    - NVL
    - NVL2
    - NULLIF
    - COALESCE
    - DECODE
    - CASE
- Numeric
    - ABS
    - ROUND
    - CEIL
    - FLOOR
    - MOD
    - POWER
    - SQRT
    - TRUNC
    - TO_CHAR
    - TO_NUMBER
- Date
    - SYSDATE
    - ADD_MONTHS
    - MONTHS_BETWEEN
    - NEXT_DAY
    - LAST_DAY
    - EXTRACT
    - TO_CHAR
    - TO_DATE
    - TO_NUMBER
    - TO_TIMESTAMP

## Window Function
Melakukan perhitungan di sekelompok baris yang berhubungan dengan baris saat ini.
contoh:
- ROW_NUMBER
- RANK
- DENSE_RANK
- LAG
- LEAD