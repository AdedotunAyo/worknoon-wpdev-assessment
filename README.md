# Worknoon WordPress Assessment

## Overview

This project is a WordPress landing page built to demonstrate practical skills in web development, SEO implementation, and system thinking. The goal was to create a clean, responsive, and performance-focused page while also showing understanding of structured data and search visibility.

## Setup Instructions

1. Install WordPress on a local or live server
2. Install and activate the Divi Theme
3. Import the layout:

   * Go to Divi Builder
   * Click the Portability icon
   * Import `WorknoonSEOLandingPage.json`
   * You can find the full steps in 'notes.md'
4. Install required plugins:

   * Forminator (for contact form)
   * Site Kit by Google (for analytics)
   * WP-Optimize (for optimization)
5. Apply custom styling:

   * Go to Divi → Theme Options → Custom CSS
   * Paste contents of `custom.css`
6. Add integration scripts (if applicable):

   * Go to Divi → Theme Options → Integration
   * Paste contents of `integration.html`

## Tools and Technologies Used

* WordPress (CMS)
* Divi Builder (page builder)
* Forminator (form handling)
* Site Kit by Google (analytics integration)
* WP-Optimize (performance optimisation)
* Custom CSS

## Features Implemented

* Responsive landing page design
* SEO-focused content structure
* Contact form integration
* Google Analytics integration
* Performance optimisation
* Clean UI with modern styling

## SEO and Schema Explanation

Structured data was created using JSON-LD format to define key entities:

* Organization schema for Worknoon
* Website schema for search functionality
* Person schema to represent leadership entity

These schemas are linked using `@id` to form a connected entity structure, helping search engines better understand relationships between the brand, website, and people.

## System Architecture Overview

The project follows a simple but effective structure:

* Frontend: Built using Divi Builder for rapid layout creation
* Styling: Enhanced with custom CSS for improved UI
* Data Capture: Forminator handles user input and submissions
* Analytics: Site Kit integrates Google Analytics for tracking
* SEO Layer: Structured data improves search engine understanding

Each component works together to support user experience, data tracking, and search visibility.

## Challenges and Solutions

One challenge was maintaining a balance between simplicity and functionality. This was solved by focusing only on essential sections and avoiding unnecessary complexity.

Another challenge was implementing schema correctly without using unverified data. This was addressed by extracting real information from the website source and avoiding assumptions.

## Reflection

This project demonstrates my ability to build a functional and scalable WordPress solution while considering SEO, performance, and system design. The focus was on creating a clean, efficient structure that aligns with real-world requirements and best practices.
