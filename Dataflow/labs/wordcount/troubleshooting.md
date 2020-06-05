# Troubleshooting
###  ⚠️  Dataflow API is not enabled.
**_Solution_**

Enabling an API in your Google Cloud project
1. In the Cloud Console, go to APIs & services for your project.
2. On the Library page, search `Dataflow API`
3. In the page that displays information about the API, click Enable.

### ⚠️  Missing required option: region
**_Solution_**

If you use the Apache Beam SDK for Java 2.15.0 or later, you must also specify `region` parameter in pipeline execution.

### ⚠️ ValueError: Unable to get filesystem from specified path
ValueError: Unable to get filesystem from specified path, please use the correct path or ensure the required dependency is installed, e.g., pip install apache-beam[gcp].

**_Solution_**
install package apache-beam[gcp]. `pip install apache-beam[gcp]`