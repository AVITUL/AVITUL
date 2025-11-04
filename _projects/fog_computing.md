---
layout: page
title: Fog Computing framework for protocol verification and performance analysis
description: Oct 2017 - Present
importance: 5
category: work
---

A Node.js based project to implement Fog Computing framework. Aim of the project was to understand the delays, throughput and efficiency of schemes proposed for Fog computing.

There are 3 layers in the project.

1. Terminal Devices / IoT layer
2. Fog layer
3. Cloud

Terminal devices were implemented on an Andorid Phone with terminux running Node.js. The application emulated behavior of real-time sensors.

Raspberry Pi 3 was used as a Fog node, which takes sensor readings from IoT devices as input, then aggregates the data. Deduplicates the data, with the help of local cache. New data or non-duplicate data is then forwarded to the Cloud.

A Dell laptop running Node.js app was used to emulate the Cloud behavior. Time stamps were appended to all the requests to calculate throughput.

Associated with National Institute of Technology Kurukshetra.
