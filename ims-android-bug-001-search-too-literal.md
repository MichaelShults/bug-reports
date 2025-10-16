**Bug Report for the IMS (Israel Meteorological Service) Android app**

**Date**: 16/10/2025  

## Title
City selection search is too literal to query.

## Description
City selection search is too literal to the query. Misses results which are valid spelling variation of a city name.

## Steps to Reproduce
1. Open the IMS app
2. Click the city selection drop down
3. Type "תל אביב" and observe results
4. Delete query
5. Now, type "תל-אביב" and observe results

## Expected Result
Both queries return two results for Tel Aviv: "תל אביב-יפו" and "תל-אביב, חוף"

## Actual Result
1. The "תל אביב" query returns only "תל אביב-יפו"
2. The "תל-אביב" query returns only "תל-אביב, חוף"

## Environment
IMS app version: 1.4.8  
OS: Xiaomi HyperOS 2.0.10.0 (based on Android 14)

## Severity
Medium (Some users may not be aware of weather data that is relevant to them)

## Screenshots
<img width="50%" src=".\screenshots\ims-android-bug-001-search-too-literal-screenshot-1.jpg" alt="תל אביב" />
<br>
<br>
<img width="50%" src=".\screenshots\ims-android-bug-001-search-too-literal-screenshot-2.jpg" alt="תל-אביב" />
