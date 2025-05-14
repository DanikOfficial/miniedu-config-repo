# 🛠️ MiniEdu Config Repository

This is the **central configuration repository** for the [MiniEdu](https://github.com/DanikOfficial/MiniEdu) microservices platform, used in conjunction with the [Spring Cloud Config Server](https://cloud.spring.io/spring-cloud-config/). It enables centralized and version-controlled configuration management for all microservices in the ecosystem.

---

## 📚 What Is This?

This repository provides externalized `.yml` or `.properties` configuration files that are loaded at runtime by the `miniedu-config-server`. These configurations are applied to services like:

- `user-service`
- `email-service`
- `course-service`
- *(and more to come)*

---

## 📁 Directory Structure

```bash
miniedu-config-repo/
├── application.yml           # Global default configuration
├── user-service.yml          # User Microservice config
├── email-service.yml         # Email Microservice config
└── ...                       # Other microservice configs

