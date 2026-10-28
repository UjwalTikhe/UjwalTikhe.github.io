---
title: "UDTC: Field Drug Testing Companion"
excerpt: "Smart India Hackathon 2026 Android app that reads reagent test colours with CIEDE2000 colorimetry and seals every test in a tamper-evident SHA-256 hash chain with dual-officer ECDSA signatures."
collection: portfolio
---

**UDTC** is an Android companion for field officers, built for the Smart India Hackathon 2026.

* Reads reagent test colours using CIEDE2000 colorimetry, with blur detection and lighting correction instead of judging by eye.
* Stores every test in a SHA-256 hash chain with an on-device tamper check, dual-officer ECDSA signatures, and GPS and time watermarks on evidence photos, following NDPS Act Section 52A.
* Works offline and sends an SMS witness record when there is no data connection.

**Stack:** Flutter, Dart, SQLite, Android Camera2, SHA-256, ECDSA, GitHub Actions
