# 📊 ClinOne eConsent Analytics Dashboard (Power BI)
## 👥 Team Members

Laxmi Sheoran

Himanshu

Vipin

Vibhor Goyal

## 📌 Project Overview

This repository contains a comprehensive Power BI analytics dashboard developed for the ClinOne eConsent platform.
Our team built this solution to provide sponsors, CROs, and clinical operations teams with complete visibility into the electronic consent lifecycle across global clinical trials.

The dashboard integrates multiple datasets to deliver insights on consent volume, signer activity, video consent usage, and document review behavior.

## 🎯 Purpose of the Dashboard

### The main goal of this Power BI report is to enable:

✔ Operational monitoring of consent progress

✔ Compliance tracking for regulatory requirements

✔ Identification of bottlenecks in signature workflows

✔ Performance comparison across countries, sites, and protocols

✔ Engagement measurement via review time and video sessions

✔ Data-driven decisions for clinical teams

This solution acts as a centralized platform for eConsent performance and audit readiness.

## 🧩 Dashboard Pages & Features
** 1️⃣ Consent Usage **

Total consents created

Pending, Completed, Declined, Archived breakdown

Manual vs Electronic adoption

Country/site-wise distribution

Assigned date trends

Pending duration metrics

** 2️⃣ Consent Aging **

Aging of pending consents

Required vs optional signatures outstanding

Next signer identification

Aging buckets (30+ / 60+ / 90+ days)

Site-wise pending signature analysis

** 3️⃣ Consent Video **

Video sessions scheduled vs completed

Protocol & country volume comparison

Average minutes per session

Monthly session trends

** 4️⃣ Consent Signatures **

Total signatures collected

Average days to signature

Signer type breakdown (Patient, Witness, Investigator, LAR, etc.)

Delivery mode (On-site / Remote / Email / Text)

Document minutes viewed before signing

** 5️⃣ Consent Review Time **

Average review time per signature

Consent version & language analytics

Review behavior insights

 ## 🏗️ Data Model Summary

The data model includes:

Dimensions

Country

Organization

Delivery Type

Document Signer Type

Study

Site

Facts

Consent Signatures

Consent Usage

Consent Path Versions

Consent Path Version Documents

Video Sessions

Pending Signatures

Time-to-Complete Metrics

The relationships follow a structured Study → Site → Subject → Consent hierarchy.

## 🚀 Business Impact

This solution supports:

⭐ Faster consent turnaround

⭐ Improved regulatory compliance

⭐ Better site performance monitoring

⭐ Strong audit readiness (FDA / IRB / EC)

⭐ Remote/hybrid trial visibility

⭐ Enhanced patient engagement metrics

## 🛠️ Tech Stack

Power BI Desktop

DAX

Power Query (M Language)

SQL-based Data Source

ClinOne eConsent Platform Data

## 📌 Outcome

A production-ready interactive Power BI dashboard that provides 360° visibility into eConsent activity across multiple clinical trials—supporting compliance, operations, and decision-making.



