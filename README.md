# Maven Crash Course 🚀

This repository **maven-crash-course** is created to understand **Apache Maven** from basics to multi-module projects using real examples.

It covers:

* Maven fundamentals
* Parent–child (multi-module) project structure
* Dependency & build management
* Practical Maven commands using **Apache Maven 3.9.11**

---

## 🔧 Maven Version Used

```
Apache Maven 3.9.11
```

---

## 📁 Repository Structure

```
maven-crash-course/
│
├── maven-parent/
│   ├── pom.xml
│   ├── maven-child1/
│   ├── maven-child2/
│   └── src/
│
├── myapp/
│   ├── pom.xml
│   └── src/
│
└── .gitignore
```

---

## 🧩 Project 1: maven-parent (Multi‑Module Project)

This project demonstrates **Maven Parent–Child architecture**.

### 🔹 What is implemented

* Parent `pom.xml` with `packaging=pom`
* Centralized dependency & plugin management
* Multiple child modules
* Shared versioning and configuration

### 🔹 Modules

* **maven-child1** – Sample child module
* **maven-child2** – Sample child module

### 🔹 Key Concepts Learned

* Parent POM
* `<modules>` configuration
* Dependency inheritance
* Plugin inheritance
* Build once, manage everywhere concept

### ▶️ Build Parent Project

```bash
mvn clean install
```

---

## 🧩 Project 2: myapp (Standalone Maven Application)

This project focuses on **basic Maven project structure**.

### 🔹 What is implemented

* Simple Java application using Maven
* Understanding of default Maven directory layout
* Dependency management using `pom.xml`

### 🔹 Key Concepts Learned

* Maven coordinates (GAV)
* Project lifecycle
* Dependency resolution
* Packaging and running Java apps

### ▶️ Build myapp

```bash
mvn clean package
```

---

## 📌 Maven Concepts Covered

* Maven lifecycle phases
* `pom.xml` structure
* Dependencies & scopes
* Parent–child relationship
* Multi‑module projects
* Maven Wrapper (`mvnw`)
* Local repository usage

---

## 🛠 Tools Used

* Java
* Apache Maven 3.9.11
* IntelliJ IDEA
* Git & GitHub

---

## 🎯 Purpose of This Repository

This repo is meant for:

* Learning Maven step‑by‑step
* Revision before interviews
* Understanding real project structure
* Hands‑on practice with Maven commands

---

## 👤 Author

**Nayan**
B.Tech CSE | Backend Developer (Java)

---

If you are learning Maven, this repo will help you build strong fundamentals.
