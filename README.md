# 🌤 Open-Meteo API Testing – Practice Project

**API Testing Fundamentals using Postman**  
By: **Dalia Aldaja – QC Engineer**

---

## 📘 Project Overview

This project demonstrates fundamental API testing concepts using the Open-Meteo public weather API.

The objective of this project is to validate:

- API request structure
- Query parameters handling
- JSON response validation
- Error handling (Negative scenarios)
- Performance validation
- Structured test case documentation

This is a hands-on QA practice project designed to strengthen API testing skills using Postman and JavaScript assertions.

---

## 🌍 About the API

This project tests the **Open-Meteo** public weather API.

Open-Meteo is a free weather forecasting API that does not require authentication or API keys.

Official Documentation: https://open-meteo.com

---

## 🛠 Tools & Technologies

- Postman – API request execution & automation
- JavaScript – Assertions inside Postman
- JSON – Response handling
- Excel – Detailed test case documentation
- GitHub – Project hosting

---

## 🎯 Test Coverage

This project includes 10 structured API test cases covering:

### ✅ Functional Testing
- Hourly forecast validation (Temperature, Humidity, Wind)
- Daily forecast validation (Max/Min temperature)
- Multiple hourly variables
- Timezone behavior validation
- Valid forecast scenario

### ❌ Negative Testing
- Missing required parameters
- Invalid parameter format (Non-numeric latitude)
- Out-of-range coordinates
- Unsupported hourly variable

### ⏱ Performance Testing
- Response time validation (< 2000 ms)

---

## 🧪 Test Case Summary

| TC ID | Title | Type | Priority |
|-------|--------|--------|-----------|
| TC-001 | Hourly Forecast (Temp/Humidity/Wind) | Functional | High |
| TC-002 | Daily Forecast (Max/Min Temperature) | Functional | Medium |
| TC-003 | Missing Latitude Parameter | Negative | High |
| TC-004 | Missing Longitude Parameter | Negative | High |
| TC-005 | Invalid Latitude (Non-Numeric) | Negative | Medium |
| TC-006 | Out-of-Range Coordinates | Negative | Medium |
| TC-007 | Multiple Hourly Variables | Functional | High |
| TC-008 | Timezone Handling (Asia/Amman) | Functional | Low |
| TC-009 | Unsupported Hourly Variable | Negative | Low |
| TC-010 | Performance Test (<2000ms) | Performance | Medium |

Full detailed test cases available in:

`TestCases/OpenMeteo.xlsx`


