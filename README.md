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

- **Operating System:** Amazon Linux
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

![image](https://github.com/user-attachments/assets/3e97b7d5-07a3-4c7b-9241-3945a7cf86ee)
![image](https://github.com/user-attachments/assets/5d577833-bf34-407d-a3b4-3611e189eba8)
![image](https://github.com/user-attachments/assets/c20e9a6d-b72c-465e-ad44-ae59675e4e80)
![image](https://github.com/user-attachments/assets/593dafb4-9f74-4cba-b6ab-da6a909dadde)
![image](https://github.com/user-attachments/assets/d6b3553c-d0ff-4951-9fe1-b2fc8ec88d07)
![image](https://github.com/user-attachments/assets/1bd2c98b-60ca-4999-9036-ae4517b75614)




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
📄 [Download the full deployment guide (PDF)](./Guide_ELK-Stack-Deployment.pdf)

