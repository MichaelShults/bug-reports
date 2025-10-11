**Bug Report for wikimedia.org**

**Date**: 11/10/2025  

## Title
Stats page for english wikipedia has cropped text  

## Description
In the "Page views by country" box, the text for "United States of America" is displayed as "United States of A" at any zoom level in the range 25-125%

## Steps to Reproduce
1. Navigate to `https://stats.wikimedia.org/#/en.wikipedia.org`  
2. Observe the "Page views by country" box, first entry, which is the united states for September 2025  
3. Change zoom level to 25%, 50%, 75%, 100% and 125%  

## Expected Result
"United States of America" is visible fully at all zoom levels in step 3

## Actual Result
"United States of A" is displayed instead at all zoom level in step 3

## Environment
Browser: Google Chrome Version 141.0.7390.77 (Official Build) (64-bit)  
Operating System: Windows 11 - 25H2 Home Edition  

## Severity
Minor (cosmetic bug, country name is apparent from the visible text)

## Screenshot
<img width="50%" src=".\screenshots\wikimedia-bug-001-cropped-text-stats-page-screenshot-1.png" alt="wikimedia stats page for english wikipedia has cropped text" />
