# MultiUser-WikiStats

**MultiUser-WikiStats** is a lightweight, browser-based tool designed for Wikimedia community organizers and contributors. It allows you to track the combined impact of multiple users across any Wikimedia project (Wikipedia, Wikisource, Wikidata, Commons) within a specific date range.

## 🚀 Features
- **Live User Search:** Find and add registered users in real-time using the MediaWiki Opensearch API.
- **Bulk Tracking:** Add multiple users as "chips" and calculate their total combined statistics instantly.
- **Cross-Wiki Support:** Switch between projects and languages with a single dropdown.
- **Deep Historical Data:** Unlike many dashboards, this tool fetches full retrospective data (including users with thousands of edits) using API pagination.
- **Direct Verification:** Click on any user's edit count to view their live contribution history on the wiki for the selected period.

## 🛠️ How to Use
1. **Select Project:** Choose the wiki project (e.g., Wikipedia) and language code (e.g., `pa` for Punjabi).
2. **Add Users:** Use the search bar to find and add editors.
3. **Set Dates:** Choose a start and end date for your campaign or analysis.
4. **Generate Stats:** Click "Generate Stats" to view the total edits and new pages created.

## 📁 Technical Details
- **Architecture:** 100% Client-side (HTML/JavaScript). No server or database required.
- **API:** Uses the [MediaWiki Action API](https://www.mediawiki.org/wiki/API:Main_page) via CORS.
- **Hosting:** Optimized for [GitHub Pages](https://pages.github.com/).

## 🤝 Community
Built for the **Punjabi Wikimedians** and the wider open-source community to help track events like *Wikipedia 25×25* and *Wiki Loves Punjab*.

---
Developed by [Kuldeep](https://github.com/kuldeepburjbhalaike)
