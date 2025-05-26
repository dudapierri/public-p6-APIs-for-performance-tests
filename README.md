# public-p6-APIs-for-performance-tests
Step by step guide on how to use docker to run k6 test APIs


# k6 Test API - Local Setup Guide

This repository contains the necessary files to run the **k6 test API** locally.

The **only way to follow along** with the examples is to run this API on your local machine.

---

## 🚀 How to Get Started

Follow these steps to set up the environment and run the API:

### ✅ 1. Install Docker

- Download and install **Docker Desktop**:  
  https://www.docker.com/products/docker-desktop

---

### ✅ 2. Download the Project Code

- Download the **k6 test-api project** as a `.zip` file.  
- Unzip the archive to a location of your choice.

---

### ✅ 3. Open Terminal

- Open a **terminal window** inside the directory containing the **unzipped source code**.

---

### ✅ 4. Start the API

Run the following command:  

```
docker-compose up -d
```

⚠️ **Note:** It may take **up to 5 minutes** to start for the first time.

---

### ✅ 5. Access the Application

- Open your browser and go to:  
  http://localhost:8000/

---

### ✅ 6. Replace API Endpoint in Tests

For all upcoming test examples, **replace**:  

```
https://test-api.k6.io/
```

with:  

```
http://localhost:8000/
```

---

### ✅ 7. Stop the API

When you are done, you can **stop** the API with the following command:  

```
docker compose down
```

---


---

Happy testing! 🚀

