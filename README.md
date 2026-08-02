# nyc-taxi-pipeline-analysis

# Cloud Data Engineering & Analytics Pipeline: NYC Taxi Case Study

An end-to-end data intelligence project designed to ingest, clean, and analyze over 3 million real-world transactional records (~120MB) utilizing cloud architecture and modern analytical tools.

## Key Architecture & Workflow:
* **Cloud Ingestion:** Configured automated pipelines inside **Azure Data Factory** utilizing wildcard paths to scale and ingest multi-month data blocks.
* **Data Cleansing (ETL):** Developed rigorous programmatic filter logic to isolate and eliminate corrupted transactional data entries (e.g., handling negative fares, zero distances, and invalid dates).
* **Optimization:** Engineered pipeline storage configurations to consolidate distributed data chunks into a single, optimized **Parquet** analytical table.
* **Local Processing:** Utilized **DuckDB** to execute hyper-fast local SQL analytical queries within a **Jupyter Notebook** environment, bypassing cloud permission latency.
* **Data Visualization:** Built interactive Python charts mapping out time-series demand spikes and operational revenue impacts.
