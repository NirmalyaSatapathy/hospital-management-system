# 🏥 HospitalManagement

A Java-based Hospital Management System built using Maven, Hibernate, MySQL, JSF (JavaServer Faces), and Jersey (RESTful Web Services).

---

## 📦 Project Structure

- **Packaging:** WAR (Web Application Archive)
- **Java Version:** 1.8
- **Build Tool:** Maven
- **Frameworks & Libraries:**
  - Hibernate (ORM)
  - JSF (Frontend)
  - Jersey (RESTful API)
  - MySQL Connector
  - JSTL (JavaServer Pages Standard Tag Library)

---

## 🧰 Technologies Used

| Tech            | Version     |
|-----------------|-------------|
| Java            | 1.8         |
| Hibernate       | 4.3.5.Final |
| JSF API         | 2.2.20      |
| JSF Impl        | 2.2.14      |
| Jersey          | 4.0.0-M2    |
| MySQL Connector | 8.0.30      |
| JSTL            | 1.2         |
| Maven Compiler  | 3.13.0      |
| Maven WAR       | 3.4.0       |

---

## ⚙️ Configuration

### 1. **Database**
Set up a MySQL database and configure Hibernate accordingly (usually in `hibernate.cfg.xml` or a similar config file).

```sql
CREATE DATABASE hospital_db;
