# Bed Management module

## Overview

The Bed Management module provides backend services and REST APIs to manage hospital beds, wards, and patient bed assignments.
It is commonly used in inpatient (IPD) workflows to track bed availability and patient occupancy.

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

---

## Running with OpenMRS SDK

1. Set up and start an OpenMRS SDK server:
   ```bash
   mvn openmrs-sdk:setup
   mvn openmrs-sdk:run
   ```
  
  ```md
  
  ```
## Troubleshooting

### Module does not appear after startup
- Ensure the `.omod` file is placed in the correct OpenMRS modules directory.
- Restart the OpenMRS server after copying the module.

### Build fails due to Java version
- Use Java 8 or Java 11.
- Avoid Java 17 or later versions, as they may cause build issues.
