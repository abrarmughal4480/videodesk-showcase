# VideoDesk — Real-Time Property Inspection Platform

> **Client work — source code is private.** This repository is a public case study describing the architecture and engineering. No client code, credentials, or proprietary assets are included.

## Overview

VideoDesk is an enterprise property-inspection SaaS I designed and built solo as the sole developer. Four distinct user roles — Super Admin, Company Admin, Landlord, Resident — each with separate dashboards, permission hierarchies, and independent workflows.

## Key engineering

- **Native WebRTC** peer-to-peer video calling (2-way & 1-way) with real-time pointer tracking
- **Live HTML5 canvas annotation** over video — 5 drawing tools, 12 colors
- **In-call recording** via MediaRecorder, real-time chat, Socket.IO push notifications
- **GPT-4 Vision Damp & Mould Analyser** — 5-level severity classification, UK-standard reports, TTS output
- **AWS S3 media pipeline** with hash-based duplicate detection and timed access codes
- Full session analytics, OTP authentication, GDPR-compliant data handling, STUN/TURN NAT traversal, support tickets, demo-meeting booking

## Tech stack

`Next.js 14` `Express.js` `Socket.IO` `WebRTC` `MongoDB` `AWS S3` `OpenAI GPT-4 Vision`

## Screenshots

Redacted screenshots coming soon.

---

Built by [Muhammad Abrar](https://github.com/abrarmughal4480) — full-stack developer specializing in real-time systems and AI integration.
