# DPL Website – Exploratory Bug Report

## Overview
This repository contains an exploratory testing report of the DPL website.  
The aim was to identify UI, usability, and W3C HTML compliance issues through manual testing.  
This report serves as both constructive feedback for DPL and a demonstration of my QA skills.

## Testing Scope
- **Platform:** Dell Latitude E5450, Windows 11  
- **Browser:** Google Chrome (latest)  
- **Tools Used:** Chrome DevTools, W3C HTML Validator, Lighthouse

## Key Findings
1. **Navbar UI Issues**
   - Layout disturbance when navigating between pages.
   - Services dropdown not fully visible and non-scrollable.

2. **Form Validation Gaps**
   - Missing required field indicators (`*`) for essential inputs.
   - Phone number fields accept text without format validation.

3. **W3C HTML Validation Errors**
   - Missing `src` attributes in `<img>` tags.
   - Use of obsolete attributes like `frameborder` and `scrolling`.
   - Multiple unnecessary `type="text/javascript"` declarations.
   - Bad value assignments (e.g., `height="auto"` on `<img>`).

4. **Critical Errors**
   - JavaScript reference errors (undefined variables).
   - Duplicate HTML `id` attributes.
   - Missing CSS resource (`404` error).
   - API returning `500 Internal Server Error`.

## Purpose
- Provide actionable feedback for improving website quality.
- Showcase QA methodology and attention to detail.
- Demonstrate initiative by performing testing without a formal request.

## How to Use
1. Review the PDF bug report included in this repository.
2. Reference issue IDs for reproduction steps and screenshots.

## Contact
**Author:** Muaaz Bin Mukhtar  
**Email:** [themuaazbinmukhtar@gmail.com]  
**LinkedIn:** [(https://www.linkedin.com/in/muaaz-bin-mukhtar-b7b8142b7/)]  

---
