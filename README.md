# Bed Management module

## Overview

The Bed Management module provices backend services and REST APIs to manage hospital beds, wards, and patient bed assignments.
It is commonly user in inpatient(IPD) workflows to track bed availability and patient occupancy.

## Prerequisites
- Java 8 or Java 11
- Maven 3.6+
- OpenMRS Platform 2.x or later
- MySQL (if running with OpenMRS SDK)

## Building the Module
Clone the repository:
```bash
git clone https://github.com/openmrs/openmrs-module-bedmanagement.git
cd openmrs-module-bedmanagement
```
```maven
mvn clean install
```
---

### Running with OpenMRS SDK
```md
## Running with OpenMRS SDK
```
```bash
mvn openmrs-sdk:setup
mvn openmrs-sdk:run
```
