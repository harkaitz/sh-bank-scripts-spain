BANK SCRIPTS - SPAIN
====================

Scripts for interfacing with spanish banks.

## Features

- Convert monthly and yearly bank statements to ledger/csv formats.

## Dependencies

- pdftotext

## Help

bbva-h-csv2ldg

    Usage: bbva-h-csv2ldg [OPTS...] FILE...
    
    Convert CSV files downloaded from BBVA to ledger accounting
    files using "getaccount(1)".
    
      -b BANK    : Bank account (A:Corriente:Tesoreria:574-Bancos:BBVA)
      -e EXPENSE : Expenses (G:ServiciosExteriores:629-OtrosServicios:Desconocido)
      -i INCOME  : Income (I:OtrosIngresosGestion:759-IngresosServiciosDiversos:Desconocido)

bbva-h-pdf2csv

    Usage: bbva-h-pdf2csv FILE...
    
    Convert a BBVA monthly bank statement (in spanish) to CSV.

bbva-h-pdf2path

    Usage: bbva-h-pdf2path PDF
    
    Print a "YEAR-MONTH.pdf" basename from a BBVA monthly bank statement.

laboral-h-csv2ldg

    Usage: laboral-h-csv2ldg [OPTS...] FILE...
    
    Convert CSV files downloaded from BBVA to ledger accounting
    files using "getaccount(1)".
    
      -b BANK    : Bank account (A:Corriente:Tesoreria:574-Bancos:Laboral).
      -e EXPENSE : Expenses (I:OtrosIngresosGestion:759-IngresosServiciosDiversos:Desconocido).
      -i INCOME  : Income (G:ServiciosExteriores:629-OtrosServicios:Desconocido).

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
