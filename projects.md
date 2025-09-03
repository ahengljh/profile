---
layout: page
title: Projects
permalink: /projects/
---

## Research Projects

### Binary Compression for Software Distribution
**ACM SAC 2024** | [Paper Link](#)

Developed a novel binary compression technique that reduces software size by 15-30% through pattern folding. This project addresses the growing challenge of software bloat in modern applications.

**Key Achievements:**
- Designed pattern recognition algorithms to identify recurring patterns across multiple executables
- Implemented shared extracted pattern code mechanism allowing binaries to reuse compressed components
- Achieved compression ratios superior to traditional methods while maintaining execution performance
- **Technologies:** C++, LLVM, Binary Analysis, Pattern Recognition

---

### Mobile App Size Optimization via IR Compression
**IEEE RTCSA 2023** | [Paper Link](#)

Created a cross-file redundancy detection system for iOS apps using LLVM bitcode distribution format, addressing critical App Store size restrictions.

**Key Achievements:**
- Built shared dictionary compression framework exceeding traditional per-file compression limits
- Reduced app sizes by up to 40% for large applications
- Deployed in production environments with zero performance degradation
- **Technologies:** LLVM, iOS, Objective-C, Compression Algorithms

---

### Android Memory Management Optimization
**USENIX ATC 2020** | [Paper Link](#)

Designed and implemented Acclaim, an adaptive memory reclaim system that significantly improves user experience in Android devices.

**Key Achievements:**
- Designed Foreground Aware Eviction (FAE) to intelligently relocate memory pages
- Implemented Lightweight Prediction-based Reclaim (LWP) using machine learning
- Achieved 40% reduction in app launch latency and 60% decrease in page re-faults
- **Technologies:** Android Kernel, C, Machine Learning, Memory Management

---

### Mobile Cache Management Framework
**HotStorage 2020, Extended to FAST 2022** | [Paper Link](#)

Analyzed and optimized heterogeneous cache file behaviors to improve flash storage lifetime in Android devices.

**Key Achievements:**
- Developed online classification algorithm for hot/warm/cold cache files
- Extended to CacheSifter, reducing flash writebacks by 70%
- Maintained cache hit rates while significantly improving device longevity
- **Technologies:** Android, File Systems, Storage Systems, Data Analysis

---

## Industry Projects


### Microsoft Edge Enterprise Mobile
**Microsoft** | 2022 - 2024

Developed enterprise mobility features for Microsoft Edge on Android and iOS platforms.

**Key Achievements:**
- Implemented security protocols improving corporate data protection by 40%
- Built cross-platform synchronization for seamless desktop-mobile workflows
- Shipped features adopted by 200+ enterprise clients within first quarter
- **Technologies:** C++, Chromium, Objective-C, Java, Android/iOS

---

### iOS Applications Portfolio
**Independent Developer** | 2025 - Present

Developed and published multiple iOS applications on the App Store.

#### monait
Personal finance management app with AI-powered insights
- Intelligent expense categorization and budget tracking
- AI-driven financial insights and recommendations
- Clean, intuitive UI with dark mode support
- **Technologies:** Swift, SwiftUI, Core Data, CloudKit

#### DoggyDaily
Pet care tracking application with health monitoring features
- Comprehensive pet health and activity tracking
- Medication reminders and vet appointment scheduling
- Photo journal with milestone tracking
- **Technologies:** Swift, HealthKit Integration, Push Notifications

#### Omacase
E-commerce platform for custom phone case design
- Real-time design preview with AR visualization
- Integration with payment gateways and shipping APIs
- Custom image upload and editing capabilities
- **Technologies:** Swift, ARKit, Stripe API, Firebase

---

## Open Source Contributions

- **vLLM:** Active contributor to the popular LLM serving framework
- **Chromium:** Contributed patches for mobile browser optimizations
- **LLVM:** Submitted improvements to bitcode compression modules

## Tools & Utilities

### Memory Profiler for Android
A lightweight tool for profiling memory usage patterns in Android applications, helping developers identify and fix memory leaks.

### Binary Pattern Analyzer
An analysis tool that identifies recurring patterns in compiled binaries, useful for compression and optimization research.