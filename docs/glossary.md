# Data Analytics & Engineering Glossary

Essential terms and concepts for data professionals. Use this as a study guide and quick reference throughout your learning journey.

---

## Core Data Concepts

**ETL (Extract, Transform, Load)**: Traditional data integration pattern where data is extracted from sources, transformed outside the target system, then loaded. Best for complex transformations and when target system has limited processing power.

**ELT (Extract, Load, Transform)**: Modern pattern where raw data is loaded first, then transformed within the target system. Leverages powerful cloud computing for transformations and maintains data lineage.

**Data Pipeline**: Automated workflow that moves data from source systems through various transformation steps to final destinations. Includes error handling, monitoring, and recovery mechanisms.

**Data Lineage**: Documentation of data's journey from source to destination, including all transformations. Essential for debugging, compliance, and impact analysis.

**Data Quality**: Measures accuracy, completeness, consistency, timeliness, and validity of data. Critical for reliable analytics and business decisions.

**Data Governance**: Framework for managing data availability, usability, integrity, and security. Includes policies, procedures, and roles for data management.

---

## Database & SQL Concepts

**Normalization**: Process of organizing database tables to reduce redundancy and improve data integrity. Higher normal forms reduce storage but may increase query complexity.

**Dimensional Modeling**: Data warehouse design technique using fact tables (metrics) and dimension tables (attributes). Optimizes for analytical queries and business understanding.

**Window Functions**: SQL functions that perform calculations across rows related to the current row. Enable ranking, running totals, and comparative analytics without self-joins.

**CTE (Common Table Expression)**: Temporary named result sets that exist within a single query execution. Improve readability and enable recursive operations.

**ACID Properties**: Atomicity, Consistency, Isolation, Durability - fundamental properties ensuring database transaction reliability.

**Indexing**: Database optimization technique creating separate structures to speed up data retrieval. Trade-off between query performance and storage/update costs.

---

## Cloud & AWS Concepts

**Data Lake**: Storage repository holding raw data in native format until needed. Supports structured, semi-structured, and unstructured data with schema-on-read approach.

**Data Warehouse**: Structured repository of integrated data optimized for analytics. Uses schema-on-write approach with predefined structure and relationships.

**Serverless Computing**: Cloud model where provider manages infrastructure automatically. Users pay only for actual compute time, enabling cost-effective scaling.

**S3 (Simple Storage Service)**: AWS object storage service providing scalable, durable storage. Supports data lakes, backups, static websites, and content distribution.

**AWS Glue**: Serverless ETL service for data preparation and integration. Includes visual editor, code-based development, and automatic schema discovery.

**Amazon Athena**: Serverless query service for analyzing data in S3 using standard SQL. Pay-per-query model ideal for ad-hoc analytics and exploration.

**Amazon QuickSight**: Business intelligence service for creating interactive dashboards and visualizations. Serverless, scalable, and integrates with AWS data services.

**IAM (Identity and Access Management)**: AWS security service controlling user access to resources. Uses policies, roles, and groups to implement least-privilege access.

---

## Analytics & Visualization Concepts

**KPI (Key Performance Indicator)**: Quantifiable measures determining progress toward business objectives. Should be specific, measurable, achievable, relevant, and time-bound.

**Dashboard**: Visual display of key information and metrics, designed for quick comprehension. Should tell a story and enable actionable insights.

**Data Storytelling**: Technique combining analytics, visualization, and narrative to communicate insights effectively. Focuses on audience needs and actionable conclusions.

**Statistical Significance**: Measure indicating whether results are likely due to chance or represent real patterns. Critical for making valid business decisions from data.

**Correlation vs. Causation**: Correlation shows relationship between variables; causation proves one variable directly influences another. Understanding this prevents incorrect conclusions.

**Time Series Analysis**: Statistical technique analyzing data points ordered in time. Identifies trends, seasonality, and patterns for forecasting and planning.

---

## Development & Engineering Concepts

**Version Control**: System tracking changes to code and documents over time. Git is standard, enabling collaboration, backup, and change management.

**CI/CD (Continuous Integration/Continuous Deployment)**: Development practices ensuring code changes are automatically tested, integrated, and deployed. Improves reliability and deployment speed.

**API (Application Programming Interface)**: Set of protocols and tools for building software applications. Defines how different software components communicate.

**Data Mart**: Subject-specific subset of data warehouse designed for particular business function or user group. Provides focused, fast access to relevant data.

**Schema Evolution**: Process of modifying data structure over time while maintaining compatibility. Critical for long-term data system maintenance and growth.

**Idempotency**: Property ensuring operations can be repeated safely without changing results. Essential for reliable data pipelines and error recovery.

---

## Business Intelligence Concepts

**OLAP (Online Analytical Processing)**: Technology optimizing databases for complex analytical queries. Supports multidimensional analysis and business intelligence applications.

**OLTP (Online Transaction Processing)**: System processing real-time transactions efficiently. Optimized for concurrent users and data integrity rather than analytics.

**Fact Table**: Central table in dimensional model containing quantitative measures and foreign keys to dimension tables. Supports aggregation and analysis.

**Dimension Table**: Supporting table providing descriptive attributes for fact table measures. Enables filtering, grouping, and contextual analysis.

**Star Schema**: Dimensional model design with fact table surrounded by dimension tables. Simple structure optimizing query performance and user understanding.

**Snowflake Schema**: Normalized version of star schema where dimension tables are further normalized. Reduces storage but increases query complexity.

---

## Python & Programming Concepts

**Pandas**: Python library for data manipulation and analysis. Provides DataFrame structures similar to Excel/SQL tables with powerful data operations.

**NumPy**: Fundamental package for numerical computing in Python. Provides support for large, multi-dimensional arrays and mathematical functions.

**Matplotlib**: Python plotting library for creating static, animated, and interactive visualizations. Foundation for many other visualization libraries.

**Seaborn**: Statistical data visualization library built on matplotlib. Provides high-level interface for drawing attractive statistical graphics.

**Plotly**: Interactive visualization library creating web-ready plots with hover, zoom, and selection capabilities.

**Jupyter Notebook**: Web-based interactive development environment for creating and sharing documents with live code, equations, visualizations, and text.

---

## Statistical & Analysis Concepts

**Descriptive Statistics**: Methods for summarizing and describing data characteristics. Includes measures of central tendency (mean, median, mode) and variability (standard deviation, range).

**Inferential Statistics**: Techniques for making predictions or inferences about a population based on sample data. Includes hypothesis testing and confidence intervals.

**Hypothesis Testing**: Statistical method for testing assumptions about data or populations. Uses p-values and significance levels to determine if results are statistically meaningful.

**Confidence Interval**: Range of values that likely contains the true population parameter with a specified level of confidence (e.g., 95% confidence interval).

**P-value**: Probability of obtaining test results at least as extreme as observed, assuming the null hypothesis is true. Lower p-values indicate stronger evidence against null hypothesis.

**Bias**: Systematic error in data collection, analysis, or interpretation that leads to incorrect conclusions. Can occur in sampling, measurement, or analytical processes.

---

## Visualization & Design Concepts

**Chart Types**:
- **Bar Charts**: Compare categories or show distributions
- **Line Charts**: Show trends over time or continuous data
- **Scatter Plots**: Display relationships between two variables
- **Histograms**: Show frequency distributions of numerical data
- **Heat Maps**: Display data density or correlation matrices
- **Box Plots**: Show data distribution and identify outliers

**Design Principles**:
- **Clarity**: Information should be easy to understand at a glance
- **Accuracy**: Visual elements should accurately represent the data
- **Efficiency**: Minimize chart junk and maximize data-ink ratio
- **Aesthetics**: Professional appearance enhances credibility and engagement

---

## Performance & Optimization

**Query Optimization**: Process of improving database query performance through better SQL writing, indexing strategies, and execution plan analysis.

**Data Partitioning**: Technique of dividing large datasets into smaller, more manageable pieces based on specific criteria (date, region, category).

**Caching**: Storing frequently accessed data in fast-access memory to improve query response times and reduce compute costs.

**Compression**: Reducing data storage requirements through encoding techniques. Important for cloud storage costs and query performance.

**Load Balancing**: Distributing workload across multiple computing resources to optimize resource utilization and minimize response time.

---

## Security & Compliance

**Data Privacy**: Protection of personal and sensitive information from unauthorized access, use, or disclosure. Includes regulations like GDPR and CCPA.

**Access Control**: System of restricting access to data and systems based on user identity, role, and business need. Implements principle of least privilege.

**Data Encryption**: Process of converting data into coded format to prevent unauthorized access during storage (at rest) and transmission (in transit).

**Audit Trail**: Record of data access, modifications, and system activities for compliance, security monitoring, and debugging purposes.

**PII (Personally Identifiable Information)**: Any data that could potentially identify a specific individual. Requires special handling and protection measures.

---

## 🔗 Study Tips

### Using This Glossary
- **Regular Review**: Revisit terms weekly to reinforce understanding
- **Practical Application**: Try to use new terms in your project documentation
- **Cross-References**: Notice how terms relate to each other across different categories
- **Real Examples**: Look for these concepts in your daily project work

### Expanding Your Knowledge
- **Official Documentation**: Read vendor documentation for detailed technical information
- **Industry Blogs**: Follow data professionals who explain concepts in practical terms
- **Online Courses**: Take focused courses on specific areas of interest
- **Hands-On Practice**: The best way to learn is by applying concepts in your projects

---

## 🔗 Navigation

- **[← Step-by-Step Activities](activities.md)** - Return to detailed learning activities
- **[Career Resources →](career.md)** - Professional development and job preparation
- **[Project Details](projects.md)** - Detailed project descriptions
- **[Quality Standards](quality.md)** - Project completion criteria
- **[Learning Overview](overview.md)** - Overall learning path structure