---

layout: col-sidebar
title: OWASP CWE Toolkit
tags: cwe weakness cve capec
level: 2
type: easy and accessible tooling to analyze, organize and manage CWE data 
pitch: 

---

## Mission

CWE Toolkit project aims to provide toolset that enables application security engineers to easily manage, manipulate and organize security data based on the CWE dataset.

## Why CWE Toolkit?

The CWE Toolkit project addresses a key concern in which CWE data is hard to access programatically and perform various automations around it, such as filtering security vulnerabilities (CVEs) based on their CWE identifier, their relationships or a string matched expression.

The goal of the CWE Toolkit project is to provide code SDKs and general tooling to programmatically manage CWE data based on APIs and Command Line utilities.

## Project Roadmap

Following is a proposed project roadmap:

* Create an easily consumable CWE dataset in various formats (currently, this data is exposed in limited format types)

* Build an application language SDK, prioritizing Node.js first as package which due to its JavaScript core can also benefit frontend OWASP projects like DefectDojo, Dependency Track and others.

* Build a command line application that is based on the SDK and allows to manage CWE data for one-off usage from a command prompt, a CI pipeline or other common CLI uses.

* Serve an HTTP API to allow easy interaction with the CWE dataset in an online manner.

