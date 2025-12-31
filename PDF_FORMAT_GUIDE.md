# PDF Format Guide

## Overview
This tool extracts data from PDF marketing reports. Your PDFs should be **text-based** (not scanned images) and follow a consistent format each month.

## Required Elements

### 1. Month Identifier
Include the month and year somewhere in the PDF:
```
November 2025
or
Marketing Report - August 2024
```

### 2. Traffic Channels
List channels with their session counts:

**Supported Channels:**
- Direct
- Organic Search
- Paid Search
- Organic Social
- Paid Social
- Referral

**Example Format:**
```
Direct: 2,032
Organic Search: 1,083
Paid Search: 494
Organic Social: 62
Paid Social: 46
Referral: 62
```

Or in a table:
```
Channel          Sessions
Direct           2,032
Organic Search   1,083
Paid Search      494
```

### 3. Location Data (Optional but Recommended)
List cities/locations with session counts:

```
Montreal: 1,020
Toronto: 310
Pointe-Claire: 295
```

### 4. Google Ads Data (Optional)
Include these metrics if you track Google Ads:

```
Clicks: 561
CTR: 5.42%
Conversions: 38
Conversion Rate: 6.77%
```

Or in a row format:
```
561    5.42%    38    6.77%
(Clicks) (CTR) (Conversions) (Conv. Rate)
```

### 5. Google Business Profile (Optional)
Include these metrics:

```
Business Profile Impressions: 5,864
Business Profile Interactions: 804
Calls: 0
Directions: 336
Website Clicks: 243
```

## Important Notes

### ✅ DO:
- Use consistent formatting across all monthly reports
- Include numbers with or without commas (both work: "1,020" or "1020")
- Use percentages with the % symbol ("5.42%")
- Keep channel names consistent ("Direct" not "Direct Traffic" one month and "Direct" the next)

### ❌ DON'T:
- Use scanned images instead of text PDFs
- Change channel names between months
- Mix different formats between months
- Include only charts without numerical values

## Testing Your PDFs

1. Open your PDF and try to select/copy text
2. If you can select text → ✅ Good to go!
3. If you can't select text → ❌ It's a scanned image, won't work

## Example PDF Structure

```
Marketing Performance Report
November 2025

Overall Sessions: 3,779

Traffic Channels:
Direct: 2,032
Organic Search: 1,083
Paid Search: 494
Organic Social: 62
Paid Social: 46
Referral: 62

Top Cities:
Montreal: 1,020
Toronto: 310
Pointe-Claire: 295

Google Ads Performance:
Clicks: 561
CTR: 5.42%
Conversions: 38
Conversion Rate: 6.77%

Google Business Profile:
Impressions: 5,864
Interactions: 804
Calls: 0
Directions: 336
Website Clicks: 243
```

## Getting Help

If your PDFs aren't being recognized:
1. Check the browser console (F12) for detailed extraction logs
2. Verify your PDF contains searchable text
3. Ensure your format matches the examples above
4. Open an issue on GitHub with a sample (anonymized) PDF

## Customization

The tool uses regex patterns to extract data. If you need to support a different PDF format, you can modify the extraction patterns in the JavaScript code. Look for the `extractPDFData` function.
