# 🔍 ELK Stack Deployment on Linux (Elasticsearch, Logstash, Kibana, Filebeat)

## 📌 Overview

This project provides a comprehensive, manual deployment guide for the ELK Stack (Elasticsearch, Logstash, Kibana) and Filebeat on **CentOS 7** using binary installations. The deployment is designed to collect, process, store, and visualize logs from multiple environments including **Test**, **QA**, **Demo**, and **Production**.

> ⚙️ Suitable for DevOps Engineers and System Administrators seeking hands-on experience configuring ELK without package managers.

---

## 📁 Components

| Component     | Description                                                    |
|---------------|----------------------------------------------------------------|
| **Elasticsearch** | Distributed, RESTful search engine for log storage and indexing |
| **Logstash**      | Log processor for collecting and transforming data           |
| **Kibana**        | Dashboard UI for Elasticsearch visualizations                 |
| **Filebeat**      | Lightweight log shipper installed on remote systems          |

---

## 🛠️ Setup Highlights

### 🔧 Manual Installation (Binary)
- Download and extract tarballs for each ELK component
- Create system users for service isolation
- Setup systemd service units for Elasticsearch, Logstash, Kibana, and Filebeat
- Adjust system limits (`nofile`, `vm.max_map_count`, memory lock, etc.)
- Configure `*.yml` files with proper ports, hosts, log paths, and pipeline settings

### 🔐 Security
- Enabled X-Pack security module for Elasticsearch and Kibana
- Setup user authentication and passwords
- Integrated Kibana with Elasticsearch using basic auth

### 📊 Kibana Dashboards
- Created index patterns in Kibana
- Set up visualizations for log monitoring
- Used Dev Tools to validate index creation (`GET _cat/indices`)

---

## 🌐 Architecture Diagram

![image](https://github.com/user-attachments/assets/97ec94ee-e54c-4b3b-bceb-65cf6dbaefff)



---

## 🔥 Technologies Used

- **Operating System:** CentOS 7
- **Elasticsearch:** v8.11.1
- **Kibana:** v8.8.2
- **Logstash:** v8.11.2
- **Filebeat:** v8.11.1
- **YAML / systemd / firewall-cmd**

---

## 🧠 Key Skills Demonstrated

- Linux System Administration
- ELK Stack Configuration
- Shell Scripting
- Log Ingestion Pipelines
- Infrastructure Observability
- Secure Configuration with X-Pack
- Custom systemd Service Management

---

## 📸 Screenshots (Optional)

_Add Kibana screenshots here to show dashboards, log visualizations, or index patterns._

---

## 📚 References

- [Elastic.co ELK Documentation](https://www.elastic.co/guide/en/)

---

## 👨‍💻 Author

**Viraj Ariyasinghe**  
DevOps / Systems Engineer

---

## ✅ License

This guide is open for learning and contribution. Feel free to fork and extend.

