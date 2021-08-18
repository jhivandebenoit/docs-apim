# Streaming Integration Overview

This section helps you to understand streaming integration and how to perform it with WSO2 Streaming Integrator in less than 30 minutes

First, let's understand the concept of streaming integration. For this, let's consider an example of a sweet factory where the system publishes the production details after each production run. The details published include the name of the sweet and the amount produced.


![Streams]({{base_path}}/assets/img/streaming/quick-start-guide-101/stream.png)

Each production run that reports the name of the sweet and the amount is an **event**.

Many such events form a **stream**.

In Streaming typically involves handling data received/published via streams in high speed and high volume. In this example, there can be multiple factories in several locations that results in a few production runs being reported in a given second.

WSO2 Streaming Integrator allows data to be received from multiple sources such as files, databases, cloud-based applications, and streaming messaging systems (such as Kafka) in a streaming manner. It uses the [Siddhi Query Language](https://siddhi.io/en/v4.x/docs/query-guide/), to process this data, and then publishes the results in a streaming manner to multiples destinations such as files, databases, cloud-based applications, and streaming messaging systems in a streaming manner.

**Streaming Integration** involves processing streaming data and incorporating them into integration flows so that action can be taken based on the output derived. In this example, you may want to filter production details relating to a specific sweet.

To understand how Streaming Integration is performed via the WSO2 Streaming Integrator, follow the sections below.

- [**Step 1: Download Streaming Integrator and Dependencies**]({{base_path}}/streaming/getting-started/download-install-and-start-si)
- [**Step 2: Create the Siddhi Application**]({{base_path}}/streaming/getting-started/create-the-siddhi-application)
- [**Step 3: Deploy the Siddhi Application**]({{base_path}}/streaming/getting-started/deploy-siddhi-application)
- [**Step 4: Run the Siddhi Application**]({{base_path}}/streaming/getting-started/test-siddhi-application)
- [**Step 5: Update the Siddhi Application**]({{base_path}}/streaming/getting-started/update-the-siddhi-application)
- [**Step 6: Handle Errors**]({{base_path}}/streaming/getting-started/handle-errors)
- [**Step 7: Monitor Statistics**]({{base_path}}/streaming/getting-started/monitor-statistics)