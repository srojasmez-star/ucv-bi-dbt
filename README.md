# Laboratorio 07 - Gold, KPIs y OLAP

Implementación de la capa Gold con dbt.

Modelos incluidos:

- dim_date
- dim_product
- dim_customer
- dim_store
- fact_sales
- kpi_sales_monthly

Validaciones realizadas:

- tests de not_null
- tests de unique
- tests de relationships
- KPI mensual
- operaciones OLAP: Slice, Dice, Drill-down y Roll-up
- lineage Bronze → Silver → Gold