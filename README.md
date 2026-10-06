# Awesome-Cloud-Big-Data-Processing-Hadoop-Spark

# Awesome-Cloud-Big-Data-Processing-Hadoop-Spark 🐘 ⚡



<p align="center">

  <img src="assets/banner.svg" alt="Awesome Cloud Big Data Processing Hadoop Spark Banner" width="100%">

</p>



<p align="center">

  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>

  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>

  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark?style=social" alt="GitHub_Stars"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark?style=social" alt="GitHub Forks"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark?color=blue" alt="License"/></a>

  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</p>



---



## 🌟 Top Cloud Big Data Processing (Hadoop / Spark) Ecosystem



**Curated List of Commercial Big Data Platforms & Open-Source Processing Frameworks**  

*Focused on Managed Spark/Hadoop Services, Lakehouse Architectures, Query Engines, Batch & Stream Processing*



**Last updated: October 2026** 📅



---



### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **cloud big data processing platforms**, **open-source Spark and Hadoop distributions**, and **managed lakehouse services**. Whether you are looking for enterprise-grade commercial solutions (such as *Amazon EMR*, *Databricks*, and *Google Cloud Dataproc*), or self-hostable open-source alternatives (like *Apache Spark*, *Apache Hadoop*, and *Trino*), this list covers category leaders, serverless processing engines, and privacy-respecting data architectures.



---



## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)

- [📊 Star History](#-star-history)

- [🤝 Support & Sponsorship](#-support--sponsorship)

- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)



---



## 🏢 SaaS / Commercial Platforms



The cloud big data processing market spans **managed Spark/Hadoop services** that charge per-instance plus a platform uplift, and **lakehouse platforms** that meter in proprietary units (DBUs, CCUs, DCUs). **Amazon EMR** bills the underlying EC2 rate plus an **EMR uplift (~27%) on master and core nodes**; task nodes bill EC2 only with no uplift, making Spot task nodes a key optimization . EMR Serverless bills **$0.052624 per vCPU-hour and $0.0057785 per GB-hour** in us-east-1 . **Google Cloud Dataproc** charges only a **small management fee ($0.01/vCPU/hour)** on top of GCE VM pricing, making it cost-effective for pure Spark batch workloads . **Azure HDInsight** bills per node-hour with **no core-hour charge** for Hadoop/Spark, but Enterprise Security Package adds **¥0.06 per core-hour** . **Databricks** meters in **DBUs**: SQL Serverless at **$0.70/DBU** (instance cost included), SQL Pro at **$0.55/DBU**, and SQL Classic at **$0.22/DBU** . **Cloudera** meters in **CCUs** with published list prices: Data Engineering Core at **$0.07/CCU**, Data Warehouse at **$0.20/CCU**, Machine Learning at **$0.20/CCU**, and Data Hub at **$0.04/CCU** — control-plane API calls are not billed, but the resources they create are .



| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |

| :--- | :--- | :--- | :--- | :--- | :--- |

| **[Amazon EMR](https://aws.amazon.com/emr/)** ☁️ | Amazon | ~$2.0 Trillion | **EC2 rate + ~27% EMR uplift on master/core nodes**; task nodes EC2-only  | **Free tier: 750 hours of m1.small or m3.medium for 12 months** (new AWS accounts) | **AWS-native big data processing** — Managed Hadoop, Spark, Hive, Presto, and HBase clusters. EMR Serverless: **$0.052624/vCPU-hour + $0.0057785/GB-hour** (us-east-1) . Task nodes can use Spot for ~65% discount. |

| **[Databricks Lakehouse](https://www.databricks.com/)** 🧱 | Databricks | ~$43 Billion | **SQL Serverless: $0.70/DBU** (instance cost included); **SQL Pro: $0.55/DBU**; **SQL Classic: $0.22/DBU**  | **14-day free trial** for pay-as-you-go plans | **Unified analytics and AI platform** — Delta Lake, MLflow, and Unity Catalog. Serverless SQL warehouses scale elastically. Premium tier on Azure equals Enterprise on AWS/GCP . |

| **[Google Cloud Dataproc](https://cloud.google.com/dataproc)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **$0.01/vCPU-hour management fee** + GCE VM pricing  | **$300 free credits** for new customers | **GCP-native managed Spark/Hadoop** — Simplest pricing in the market: no DBU overhead, per-second billing. Integrates tightly with BigQuery, GCS, and Vertex AI. Best for **pure Spark batch processing** . |

| **[Azure HDInsight](https://azure.microsoft.com/en-us/products/hdinsight/)** 🔷 | Microsoft | ~$3.90 Trillion | **Base price/node-hour + ¥0/core-hour** for Hadoop/Spark  | **Free trial available** | **Azure-native managed Hadoop/Spark** — **Enterprise Security Package: +¥0.06/core-hour** . Supports Kafka, HBase, Storm, and Interactive Query. Billing starts at cluster creation and ends at deletion, per-minute . |

| **[Cloudera Data Platform (CDP)](https://www.cloudera.com/)** 🏢 | Cloudera | Private | **Data Engineering Core: $0.07/CCU-hour**; Data Warehouse: **$0.20/CCU**; ML: **$0.20/CCU**; Data Hub: **$0.04/CCU**  | **60-day free trial** (lead-capture gated, not self-serve)  | **Enterprise data platform** — CDP meters in **Cloudera Compute Units (CCUs)** and **CGUs** for GPU. **Control-plane API calls are not billed** — the resources they create are . On-premises subscriptions priced per CCU-year. |

| **[Qubole](https://www.qubole.com/)** 🔥 | Qubole | Private | **~$0.17/QCU-hour** (usage-based)  | **Business Edition free: 30,000 QCPU/month** on Oracle Cloud (BYOC)  | **Cloud data platform** — Spark, Hive, Presto, and TensorFlow. Business Edition on Oracle Cloud is free with your own Oracle account; **you pay Oracle directly for compute** . |

| **[Snowflake](https://www.snowflake.com/)** ❄️ | Snowflake | ~$50 Billion | **Credit-based** per warehouse size and runtime | **$400 free trial credits** (30 days)  | **Cloud data warehouse** — Hybrid tables now billed on **two categories** (storage + virtual warehouse compute) as of March 2026; per-request charges eliminated . |

| **[Starburst Galaxy](https://www.starburst.io/)** ⭐ | Starburst | Private | **Pro: $0.50/credit**; Enterprise: **$0.75/credit**; Mission-Critical: **$1.00/credit**  | **Free forever: up to 3 clusters**; 30-day trial with **$500 compute credits**  | **Managed Trino lakehouse** — Credits are a universal compute unit; a 2-worker cluster uses 12 credits/hour across all tiers . Free tier supports standard execution only. |

| **[Dremio Cloud](https://www.dremio.com/)** 🦅 | Dremio | Private | **$0.20/DCU** (Dremio Cloud)  | **$400 free trial credits**, no credit card required  | **Managed lakehouse on AWS** — Consumption-based DCU pricing. Elastic Engines scale to zero, Autonomous Reflections, and hosted MCP server. **$80,000 minimum commitment** on enterprise plans . |

| **[Ahana Cloud](https://www.ahana.io/)** ☁️ | Ahana (Acquired) | Private | **Enterprise, custom pricing** | **Free trial available** | **Managed Presto/Trino on AWS** — Ahana Cloud for Presto provides a managed query engine for data lakes. Pricing is enterprise-gated with no public list price . |



---



## 🔓 Open-Source GitHub Projects



*Sorted by GitHub_Stars_Count (Descending)* 🌟



- **[Apache Spark](https://github.com/apache/spark)** [![Stars](https://img.shields.io/github/stars/apache/spark?style=social&color=white)](https://github.com/apache/spark/stargazers)  

  **Unified analytics engine for large-scale data processing**, Apache-2.0 licensed. **~40k+ stars**. Batch processing, streaming, SQL, ML, and graph processing. Runs on Kubernetes, YARN, and standalone clusters. **The foundational processing engine for the entire ecosystem** — Amazon EMR, Databricks, Dataproc, and HDInsight all run Spark under the hood . ⚡



- **[Apache Hadoop](https://github.com/apache/hadoop)** [![Stars](https://img.shields.io/github/stars/apache/hadoop?style=social&color=white)](https://github.com/apache/hadoop/stargazers)  

  **Distributed storage and processing framework**, Apache-2.0 licensed. **~15k+ stars**. HDFS for storage, MapReduce for batch processing, YARN for resource management. **The original big data platform** — still the foundation for HDFS-based architectures . 🐘



- **[Trino](https://github.com/trinodb/trino)** [![Stars](https://img.shields.io/github/stars/trinodb/trino?style=social&color=white)](https://github.com/trinodb/trino/stargazers)  

  **Distributed SQL query engine**, Apache-2.0 licensed. **~10k+ stars**. Queries data where it lives — HDFS, S3, Kafka, RDBMS, and more. **The open-source engine behind Starburst** . PrestoSQL successor with active community development. 🔍



- **[Delta Lake](https://github.com/delta-io/delta)** [![Stars](https://img.shields.io/github/stars/delta-io/delta?style=social&color=white)](https://github.com/delta-io/delta/stargazers)  

  **Storage framework for lakehouse architecture**, Apache-2.0 licensed. **~7k+ stars**. ACID transactions, scalable metadata handling, and unified batch/streaming. **The open-source foundation of Databricks** — brings reliability to data lakes on S3, HDFS, and Azure Blob . 🏞️



- **[Apache Iceberg](https://github.com/apache/iceberg)** [![Stars](https://img.shields.io/github/stars/apache/iceberg?style=social&color=white)](https://github.com/apache/iceberg/stargazers)  

  **Open table format for huge analytic datasets**, Apache-2.0 licensed. **~6k+ stars**. Schema evolution, hidden partitioning, and time travel. **The table format used by Matano, Snowflake, Dremio, and Starburst** for open lakehouse architectures. ❄️



- **[Apache Flink](https://github.com/apache/flink)** [![Stars](https://img.shields.io/github/stars/apache/flink?style=social&color=white)](https://github.com/apache/flink/stargazers)  

  **Stream processing framework**, Apache-2.0 licensed. **~24k+ stars**. True stream processing with event-time semantics and exactly-once guarantees. **The streaming counterpart to Spark** — used where sub-second latency matters. 🌊



- **[Apache Hive](https://github.com/apache/hive)** [![Stars](https://img.shields.io/github/stars/apache/hive?style=social&color=white)](https://github.com/apache/hive/stargazers)  

  **Data warehouse software for Hadoop**, Apache-2.0 licensed. **~5k+ stars**. SQL-like interface (HiveQL) for querying data stored in HDFS. **The original SQL-on-Hadoop engine** — still widely used in legacy EMR and HDInsight deployments . 🐝



- **[Presto (Legacy)](https://github.com/prestodb/presto)** [![Stars](https://img.shields.io/github/stars/prestodb/presto?style=social&color=white)](https://github.com/prestodb/presto/stargazers)  

  **Distributed SQL query engine**, Apache-2.0 licensed. **~16k+ stars**. The original Presto project from Facebook. **Ahana Cloud was built on Presto** . Trino is the actively developed fork. 🔷



- **[Apache HBase](https://github.com/apache/hbase)** [![Stars](https://img.shields.io/github/stars/apache/hbase?style=social&color=white)](https://github.com/apache/hbase/stargazers)  

  **Hadoop database for random read/write access**, Apache-2.0 licensed. **~5k+ stars**. Column-oriented NoSQL store on HDFS. **Available in Amazon EMR and Azure HDInsight** for low-latency access to big data . 📊



- **[dbt (data build tool)](https://github.com/dbt-labs/dbt-core)** [![Stars](https://img.shields.io/github/stars/dbt-labs/dbt-core?style=social&color=white)](https://github.com/dbt-labs/dbt-core/stargazers)  

  **Analytics engineering transformation tool**, Apache-2.0 licensed. **~10k+ stars**. SQL-based transformations with version control, testing, and documentation. **The release step in DataOps pipelines** alongside Spark and Airflow . 🔧



- **[Apache Airflow](https://github.com/apache/airflow)** [![Stars](https://img.shields.io/github/stars/apache/airflow?style=social&color=white)](https://github.com/apache/airflow/stargazers)  

  **Workflow orchestration platform**, Apache-2.0 licensed. **~40k+ stars**. DAG-based pipeline scheduling with operators for EMR, Dataproc, and Databricks. **The monitoring and orchestration layer for DataOps** . 🌊



- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)** [![Stars](https://img.shields.io/github/stars/OpenLineage/OpenLineage?style=social&color=white)](https://github.com/OpenLineage/OpenLineage/stargazers)  

  **Data lineage collection framework**, Apache-2.0 licensed. **~2k+ stars**. Vendor-neutral lineage metadata for Spark, Airflow, dbt, and more. **The missing observability layer** for big data pipelines. 🔗



---



## 🛠️ How to Contribute



Contributions are welcome! Follow these steps to submit new big data processing platforms or open-source frameworks:



1. 🍴 **Fork** the repository.

2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.

3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.

4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.



---



## 📊 Star History



[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Big-Data-Processing-Hadoop-Spark&type=date&legend=top-left)



---



## 🤝 Support & Sponsorship



If you find this cloud big data processing repository useful, please consider supporting the project:



- ⭐ **Star** this repository to increase visibility!

- 🔀 **Fork** and share with fellow data engineers, platform teams, and open-source advocates.

- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).



---



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️

- **EMR uplift applies only to master and core nodes (~27%)** — task nodes bill EC2 only, making Spot task nodes a key cost optimization . **Dataproc’s $0.01/vCPU-hour management fee** is far simpler than DBU-based pricing, but lacks Databricks' Delta Lake and ML features .

- **Cloudera control-plane API calls are not billed** — but the resources they create (environments, clusters, warehouses) start CCU-hourly meters that run until deleted or stopped. This is the single most important cost fact for automation . **Cloudera’s 60-day free trial is lead-capture gated**, not self-serve .

- **Dremio Cloud has an $80,000 minimum commitment** on enterprise plans and at least 5 documented hidden costs beyond list price . **Starburst’s free tier** supports only standard execution mode — Pro tier unlocks flexible modes and streaming ingest .

- Open-source solutions (Spark, Hadoop, Trino, Delta Lake, Iceberg) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, managed infrastructure, and vendor support remain primarily commercial offerings. **Benchmark for your specific workload** — Dataproc excels at pure Spark batch, Databricks at lakehouse ML, and Cloudera at hybrid multi-cloud governance. ⚡



---



<p align="center">

  <b>Made with ❤️ for data engineers, platform teams, and open-source big data advocates.</b>

</p>
