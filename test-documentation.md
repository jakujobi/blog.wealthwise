## T25. Financial News Component

| Test Number | T1 |
| --- | --- |
| Test Module | Financial News Component |
| F/S(WBS) number | 4.1 |
| Software Setup | - **Operating System**: Windows 11 Education 24H2
- **Browser**: Microsoft Edge 134.0.3124.72 
- **Network**: Xtream 5GHz Wifi at 1201mb/s |
| Hardware Setup | - **Processor**: 13th Gen Intel(R) Core(TM) i7-1355U 1.70 GHz
- **Memory**: 32 GB |

**Purpose of module:** The Financial News component displays the latest financial news articles from the NewsAPI.org service, providing WealthWise users with up-to-date market information to enhance their financial literacy and decision-making.

**Setup:** Navigate to the WealthWise learning hub homepage where the Financial News component is displayed at the bottom of the page.

### Test Scenarios:

| ID | Test Case | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| FN-01 | Load the homepage and verify the Financial News component is visible | Component displays with "Latest Financial News" heading | | |
| FN-02 | Verify news articles are displayed (when API key is valid) | Up to 5 financial news articles are displayed with clickable links | | |
| FN-03 | Click on a news article link | Link opens the original article in a new browser tab | | |
| FN-04 | Test with invalid/missing API key | Error message "Could not load news. Please try again later." is displayed | | |
| FN-05 | Test component responsiveness on mobile device | Component maintains proper layout and readability on small screens | | |

### **Acceptance of Test**

**Date: 30 April 2025**

Signature:

Name:

**Arqer:**

Signature:

Name: 

**WealthWise:** 

---

## T26. Learning Module Blog Navigation

| Test Number | T2 |
| --- | --- |
| Test Module | Learning Module Blog Navigation |
| F/S(WBS) number | 4.2 |
| Software Setup | - **Operating System**: Windows 11 Education 24H2
- **Browser**: Microsoft Edge 134.0.3124.72 
- **Network**: Xtream 5GHz Wifi at 1201mb/s |
| Hardware Setup | - **Processor**: 13th Gen Intel(R) Core(TM) i7-1355U 1.70 GHz
- **Memory**: 32 GB |

**Purpose of module:** This test ensures that the learning module blog properly integrates with the main WealthWise platform, allowing users to navigate between educational content and the main application seamlessly.

**Setup:** Navigate to the WealthWise learning hub homepage. Verify the navigation elements, particularly the "Return to WealthWise" link in the header.

### Test Scenarios:

| ID | Test Case | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| LM-01 | Verify "Return to WealthWise" link exists in header | Link is visible in the header navigation area | | |
| LM-02 | Click on "Return to WealthWise" link | User is redirected to https://wealthwise.onrender.com | | |
| LM-03 | Test header responsiveness on mobile device | "Return to WealthWise" link is accessible in mobile menu | | |
| LM-04 | Navigate to a blog post and verify header persistence | "Return to WealthWise" link remains accessible | | |
| LM-05 | Test navigation after filtering by tags | "Return to WealthWise" link remains accessible | | |

### **Acceptance of Test**

**Date: 30 April 2025**

Signature:

Name:

**Arqer:**

Signature:

Name: 

**WealthWise:**
