# Fluidra Catalogs iOS App

A production iOS application for browsing and managing product catalogs, manuals, and region-based pricing with full offline and online support.

## Overview

The Fluidra Catalogs app provides an intuitive experience for exploring product catalogs, viewing technical manuals, checking pricing, and managing shopping lists. It is designed with an offline-first architecture to ensure reliable access to content even without network connectivity.

## Access Notice

This repository is a **read-only showcase** of a production application developed for a company.  
Source code cannot be made public due to confidentiality and intellectual property restrictions.

## Features

### Region-Based Catalogs
- Interactive region selection
- Region-specific products, pricing, and availability
- Clickable regions within catalog pages
- Region-based notes and shopping list integration

### Manuals
- In-app PDF manual viewing
- Supports technical documentation and product specifications

### Pricing
- Displays product pricing information
- Region-specific pricing support

### Shopping Lists
- Create and manage multiple shopping lists
- Add products with quantities and notes
- Email and print shopping lists (online mode)
- Offline access to saved shopping lists

### Catalog Browsing
- Dynamic catalog with section-based templates
- Responsive layouts including grids, carousels, and custom sections
- Traditional fixed-layout catalog for page-based browsing
- Supports both portrait and landscape orientations

### Analytics
- Firebase Analytics integration
- Tracks user navigation, product interactions, and catalog usage
- Provides insights into user behavior and feature engagement

### Online & Offline Support
- Automatic network detection
- Online mode with real-time data and updates
- Offline mode with cached catalogs, product data, and shopping lists

## Tech Stack

- Swift
- UIKit
- Core Data
- REST APIs
- Firebase Analytics
- PDFKit
- UICollectionViewCompositionalLayout

## Architecture

- MVC architecture
- Offline-first data flow
- REST API → Core Data → UI
- Network reachability-based feature toggling
- Reusable and configurable catalog section templates

## Key Contributions

- Built a production-grade iOS catalog application with offline-first support
- Designed dynamic and static catalog systems using reusable UI components
- Implemented region-based pricing, product availability, and interactive regions
- Integrated Firebase Analytics to monitor user behavior and feature engagement
- Developed reliable online/offline data synchronization using Core Data
