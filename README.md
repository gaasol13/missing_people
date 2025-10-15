# missing_people
Replicated database system (MySQL + MongoDB) with Python/Bash automation for collecting and managing missing persons data from Mexican digital sources.

## 🎯 Project Goals

- Build a **MySQL master-slave replication system** across multiple VMs for high availability and data redundancy
- Implement **MongoDB replica sets** for flexible document storage and querying
- Automate data collection, ETL pipelines, and database management using **Python** and **Bash**
- Develop web scrapers to gather information from local Mexican media, social media, and digital sources (long-term goal)
- Create a comprehensive, normalized database to support missing persons cases

### Tech Stack

- **Databases:** MySQL 8.0 (master-slave replication), MongoDB (replica set `rs0`)
- **Infrastructure:** VirtualBox VMs, Ubuntu 18.04, SSH tunneling
- **Languages:** Python 3 (pandas, matplotlib), Bash scripting
- **Tools:** DataGrip, Git, VS Code
- **Data Sources:** CSV files, Mexican news outlets (future), social media (future)

## 📊 Project Status

### ✅ Phase 1: Infrastructure (Complete)
- [x] Three Ubuntu VMs deployed with VirtualBox
- [x] MySQL 8.0 master-slave replication configured and tested
- [x] MongoDB replica set deployed and synchronized
- [x] SSH key authentication and tunneling established
- [x] DataGrip connections configured for all database instances
- [x] Successful MySQL 5.7 → 8.0 upgrade across all nodes

### 🚧 Phase 2: Data Pipeline (In Progress)
- [x] Python environment configured (pandas, matplotlib installed)
- [x] Initial CSV dataset imported (`tot_reg_desap.csv`)
- [ ] Data exploration and quality assessment
- [ ] Database schema design and normalization
- [ ] ETL pipeline development

### 📋 Phase 3: Automation (Planned)
- [ ] Python scripts for data cleaning and transformation
- [ ] Bash scripts for database backup and maintenance
- [ ] Automated replication health monitoring
- [ ] Cron jobs for scheduled tasks

### 🔮 Phase 4: Web Scraping (Future)
- [ ] Scrapers for Mexican news outlets
- [ ] Social media data collection modules
- [ ] Real-time data ingestion pipeline
- [ ] Data deduplication and entity resolution
