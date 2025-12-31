# 📊 Marketing Report Comparison Tool

A powerful, offline HTML tool for comparing monthly marketing performance reports. Upload PDF reports and get instant visual comparisons with automated insights and alerts.

![Marketing Comparison Tool](https://img.shields.io/badge/HTML-Standalone-blue) ![No Backend Required](https://img.shields.io/badge/Backend-Not%20Required-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## ✨ Features

### 📈 Core Analysis
- **Executive Insights** - Automatic summary of key performance changes
- **Automated Alerts** - Color-coded warnings for significant changes (🔴 Critical, 🟡 Warning, 🟢 Success)
- **Multi-Month Trend Analysis** - Visual trend lines when uploading 3+ months

### 📊 Comprehensive Reporting
- **Traffic Channels** - Compare Direct, Organic, Paid Search, Social, and Referral traffic
- **Location Performance** - City-by-city breakdown with growth metrics
- **Google Ads Metrics** - Clicks, CTR, Conversions, and Conversion Rates
- **Google Business Profile** - Impressions, Interactions, Calls, Directions, and Website Clicks

### 🎯 Smart Features
- **Works Offline** - No internet connection required after download
- **No Installation** - Just open the HTML file in any browser
- **Print/PDF Export** - One-click report generation for sharing
- **Responsive Design** - Works on desktop, tablet, and mobile

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Monthly marketing PDF reports (see format requirements below)

### Usage

1. **Download** the `marketing_comparison_tool.html` file
2. **Open** it in your web browser (double-click the file)
3. **Upload** 2 or more PDF reports by:
   - Clicking the upload area, or
   - Dragging and dropping PDF files
4. **Click** "Compare Reports" button
5. **Review** insights, alerts, and detailed comparisons
6. **Print** or save as PDF to share with stakeholders

## 📄 PDF Format Requirements

Your monthly marketing PDFs should contain the following sections:

### Required Data Points
- **Month identifier** (e.g., "November 2025", "March 2024")
- **Traffic channels** with session counts:
  - Direct
  - Organic Search
  - Paid Search
  - Organic Social
  - Paid Social
  - Referral
- **Location data** (cities with session counts)
- **Google Ads metrics** (optional):
  - Clicks, CTR, Conversions, Conversion Rate
- **Google Business Profile** (optional):
  - Impressions, Interactions, Calls, Directions, Website Clicks

### Example Format
```
November 2025

Direct: 2,032
Organic Search: 1,083
Paid Search: 494

Montreal: 1,020
Toronto: 310

Google Ads:
Clicks: 561
CTR: 5.42%
Conversions: 38
Conversion Rate: 6.77%
```

## 📊 What You Get

### 1. Executive Insights
Automatic summary showing:
- Overall session change percentage
- Biggest channel movements
- Top performing locations
- Key metric highlights

### 2. Automated Alerts
- 🔴 **RED ALERT**: Drops >50% (needs immediate action)
- 🟡 **WARNING**: Changes 25-50% (monitor closely)  
- 🟢 **SUCCESS**: Growth >50% (scale what works)
- ✅ **ALL GOOD**: Everything within normal ranges

### 3. Trend Analysis (3+ months)
- Multi-month line chart showing growth patterns
- Month-by-month comparison table
- Trend direction analysis (growing, stable, declining)

### 4. Visual Charts
- Bar charts for channel comparison
- Donut chart for traffic distribution
- Location performance charts
- Google Ads performance metrics

## 🎨 Screenshots

### Executive Dashboard
Quick overview with insights and alerts at the top.

### Trend Analysis
Multi-month trend lines showing traffic patterns over time.

### Detailed Breakdowns
Channel-by-channel, city-by-city, and platform-specific comparisons.

## 🛠️ Technical Details

- **Technology**: Pure HTML, CSS, JavaScript
- **Libraries Used**:
  - [Chart.js](https://www.chartjs.org/) - Beautiful charts
  - [PDF.js](https://mozilla.github.io/pdf.js/) - PDF text extraction
- **No Backend Required**: Everything runs in your browser
- **Privacy First**: All data processing happens locally, nothing is uploaded to servers

## 📋 How It Works

1. **PDF Text Extraction**: Uses PDF.js to extract text from uploaded PDFs
2. **Pattern Matching**: Identifies data points using regex patterns
3. **Data Normalization**: Organizes extracted data into structured format
4. **Comparison Engine**: Calculates changes between months
5. **Alert System**: Analyzes changes and generates warnings
6. **Visualization**: Creates interactive charts with Chart.js

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contribution
- Support for additional PDF formats
- More data visualization options
- Export to Excel/CSV
- Custom alert thresholds
- Historical data storage

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Chart.js](https://www.chartjs.org/)
- PDF parsing powered by [PDF.js](https://mozilla.github.io/pdf.js/)
- Inspired by the need for quick, offline marketing analysis

## 💡 Use Cases

- **Marketing Teams**: Compare monthly performance quickly
- **Agencies**: Generate client reports efficiently
- **Freelancers**: Track campaign performance over time
- **Small Businesses**: Understand marketing ROI without expensive tools

## 🐛 Troubleshooting

**Q: My PDFs aren't being recognized**
- Ensure your PDFs contain actual text (not scanned images)
- Check that data follows the expected format
- Try with the sample PDF first

**Q: Charts aren't displaying**
- Make sure you're using a modern browser
- Check browser console for errors (F12)
- Ensure JavaScript is enabled

**Q: Comparison shows identical data**
- Verify you uploaded different month files
- Check console logs for extraction details
- Hard refresh the page (Ctrl+Shift+R)

## 📧 Contact

Questions? Issues? Suggestions?
- Open an [Issue](https://github.com/yourusername/marketing-comparison-tool/issues)
- Submit a [Pull Request](https://github.com/yourusername/marketing-comparison-tool/pulls)

## ⭐ Star This Project

If you find this tool useful, please consider giving it a star on GitHub!

---

**Made with ❤️ for marketers who need quick, reliable insights**
