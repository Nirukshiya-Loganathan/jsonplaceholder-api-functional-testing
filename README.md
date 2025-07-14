# 📦 JSONPlaceholder API Functional Testing (Postman)

This project demonstrates functional testing of a public REST API using **Postman**. It's designed to help QA engineers practice writing, organizing, and executing test cases in a real-world style setup.

---

## 🔧 Tools Used
- [Postman](https://www.postman.com/)
- JSONPlaceholder Public API ([https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com))
- GitHub for version control and project documentation

---

## 🔍 API Endpoints Tested
| Method | Endpoint                       | Description                     |
|--------|--------------------------------|---------------------------------|
| GET    | `/posts`                       | Get all posts                   |
| GET    | `/posts/1`                     | Get single post by ID           |
| POST   | `/posts`                       | Create a new post (mock)        |

---

## ✅ Test Cases Include
- Status code verification (200, 201)
- Response time checks
- Field existence and data structure validation
- Basic assertion scripts using Postman Tests tab

---

## 📁 Folder Structure (Coming Soon)

```bash
jsonplaceholder-api-functional-testing/
│
├── postman_collection/
│   └── jsonplaceholder_test_collection.json
│
├── reports/
│   └── test-report-sample.png
│
├── docs/
│   └── test-plan.md
│
└── README.md
