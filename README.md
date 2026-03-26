# 🚀 Poll SCM Demo (Jenkins)

This repository demonstrates how **Poll SCM works in Jenkins Pipeline**.

---

## 📌 What is Poll SCM?

Poll SCM allows Jenkins to:

* Periodically check the Git repository
* Trigger a build when changes are detected

---

## 🛠️ Project Structure

```
poll-scm-demo/
 ├── Jenkinsfile
 ├── app.txt
 └── README.md
```

---

## ⚙️ Jenkins Configuration

* Job Type: Pipeline
* SCM: Git
* Branch: `main`
* Build Trigger: Poll SCM

### ⏱️ Schedule

```
* * * * *
```

➡️ Checks repository every 1 minute

---

## 📄 Jenkinsfile Overview

* Uses declarative pipeline
* Polls SCM for changes
* Reads content from `app.txt`

---

## 🧪
