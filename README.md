# CHANGELOG

## [2026-05-13]

**Member: Nguyen Phuc Toan**

**Done:**

* Fit response brainstorm agent with user language
* Fix error token monitor
**Todo:**
* Fix Error Crash Fonted when large scene (Backend Scale).

---

**Member: Nguyen Thanh Tuyen**

**Done:**

* Researched and proposed load testing strategy for AES using k6.
* Identified key bottlenecks, monitoring metrics, and scaling configurations.
* Evaluated server providers for stress test, staging, and production environments.

**Todo:**
* Set up staging VPS and monitoring stack (InfluxDB + Grafana).
* Prepare k6 load/stress test scenarios and dashboard structure.
* Implement MockProvider integration for LLM stress testing.

---

**Member: Truong Thanh Thang**

**Done:**

* Reviewed 4 pull requests.
* Improved the UI based on the Figma design.
* Added environment list, import, and load features.
* Added generation model selection and updated model parameters across generate endpoints.

**Todo:**

* Review pull requests.
* Update feedback handling when users hit the rate limit.
* Add an option to use the user's prompt directly.
* Fix the bug where clicking an object tag does not highlight the object, unlike right-clicking the object in the scene.
* Continue improving the UI.

---

**Member: Le Minh Duc**

**Done:**

* Added usage quota feature, limiting how many LLM apis call a user can make a day

* Converted existing RESTful asset generate endpoints to ws, added JWT as requirements in request body of 2 main generate endpoints, Added kill process feature endpoint

* Added venice as provider in monitor feature, added more tracking to monitor feature: agent, model name

* Fixed the bug where there are mismatchs between how FE and BE store scene causing objects Z-coordinate to unexpectedly change when choosing robot

* 

**Todo:**
* Find a way to ultilize 16k asset dataset without overloading front-end (pagination, keyword search, semantic search)

* Add time estimating feature to time-taking feature like generate

---

