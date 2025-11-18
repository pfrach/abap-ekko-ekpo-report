##ABAP Purchase Order Viewer (EKKO/EKPO) - SALV Report##

This ABAP report displays purchasing document data from **EKKO** and **EKPO** tables with user-defined selection criteria.
The output is rendered using **CL_SALV_TABLE**, providing a clean, ALV-style table.

#Features:

* Filter purchase orders by:

  * Purchase Order Number (EBELN)
  * Document Date (BEDAT)
  * Company Code (BUKRS)
  * Material Number (MATNR)

* Reads and combines data from **EKKO** and **EKPO**
* Displays:

  * PO header and item data
  * Material information
  * Quantities, UoM, and pricing

* Lightweight and fast (limit: 50 rows for demo purposes)
* Clean SALV display using standard SAP framework

#Purpose:

This project demonstrates:

* Practical ABAP SQL joins
* Clean SALV table usage
* SAP MM Purchasing data extraction
* A simple, real-world SAP use case suitable for beginners and job portfolio
