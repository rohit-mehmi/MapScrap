MapScrap

A lightweight, single-page web tool for discovering and evaluating local businesses using Google Maps data.

Developed by Rohit Mehmi.

Overview

MapScrap queries the Serper Places API to extract business listings based on category and location parameters. The tool identifies businesses without an active website, provides quick-contact shortcuts, generates structured LocalBusiness schema, and supports CSV data export.

Features

Data Extraction: Retrieves business names, addresses, phone numbers, ratings, review counts, and direct Google Maps URLs.

Website Detection: Filters listings to highlight businesses without an active website.

Direct Dialing: Phone links formatted with standard tel: protocols for immediate calling.

Schema Generation: Automatically formats basic schema.org/LocalBusiness JSON-LD markup.

Message Templates: Provides pre-formatted outreach copy for email, WhatsApp, or SMS.

Filters and Export: Filter results by website availability or review counts (< 50) and export full datasets to CSV.

Zero Dependencies: Implemented as a single standalone HTML file requiring no package managers, build steps, or server-side runtimes.
