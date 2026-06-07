2: Data Ingestion and Loading (21%)
● Enable and detail data ingestion patterns, including batch, streaming, and incremental
loading, and import data from sources such as local files, Lakeflow Connect standard
connectors, and Lakeflow Connect managed connectors.
● Use the COPY INTO command to incrementally load files from cloud object storage
(ADLS/S3/GCS) into Unity‑Catalog–governed tables.
● Use Auto Loader with schema enforcement and schema evolution in batch modes (for
example, directory listing or file notification) to land data into UnityCatalog–governed
tables.
● Configure Lakeflow Connect to reliably ingest data from diverse enterprise sources into
UnityCatalog–governed tables.
● Use JDBC/ODBC or REST clients in notebooks to land data into cloud storage or directly into
UnityCatalog–governed tables, usually orchestrated and scheduled with Lakeflow Jobs.
● Prioritize between Auto Loader, Lakeflow Connect (standard and managed connectors),
partner connectors, and other ingestion methods based on technical requirements such as
data volume, ingestion frequency, data types, and governance needs with Unity Catalog.
● Ingest semi-structured and unstructured data (for example, JSON and nested data) via
Lakeflow Connect and other managed connectors into UnityCatalog–governed Delta tables.


