📄 Manual Test Cases – X Careers Notification System

📘 1. Introduction

The objective of this document is to provide a detailed list of **manual test cases** that validate the core functionality, user interface, integrations, and workflows of the X Careers platform.

The system includes:

- X Careers Web Application  
- NotifyX Subscription System (₹49/month)  
- Admin Job Posting & Notification Module  
- Email Notification Delivery  
🎯 2. Scope of Testing

The test cases cover:
- Navigation  
- Search Functionality  
- Course & Job Listings  
- Form Validations  
- Subscription Flow  
- Email Notification  
- UI/UX  
- Responsiveness  
- Footer & Header Elements  
- Job & Course Detail Pages

3. Test Case Format

Each test case includes:
- Test Case ID 
- Scenario  
- Description 
- Preconditions 
- Test Steps 
- Test Data
- Expected Result  
- Type 
- Priority

✅ 4. Manual Test Cases

Navigation Test Cases

## 🧭 Navigation Test Cases

| TC ID | Test Case Description | Pre-Conditions | Test Steps | Expected Result | Status |
|------|------------------------|----------------|-------------|-----------------|---------|
| NAV-001 | Verify user can navigate to Home page from any page | User is on any page | 1. Click on **Home** menu option | User is redirected to Home page successfully | Pass/Fail |
| NAV-002 | Verify that the Login page opens when clicking Login button | None | 1. Click on **Login** button in header | Login page loads with email & password fields | Pass/Fail |
| NAV-003 | Verify user can navigate to the Register/Signup page | None | 1. Click **Sign Up** from header | Register page opens successfully | Pass/Fail |
| NAV-004 | Verify navigation to the "Job Listings" page after login | User must be logged in | 1. Click on **Jobs** section | Job listings page loads | Pass/Fail |
| NAV-005 | Verify navigation to the Profile page | User must be logged in | 1. Click on **Profile** icon/menu | Profile page opens with user details | Pass/Fail |
| NAV-006 | Verify navigation to the Subscription page | User must be logged in | 1. Click **Subscription** from menu | Subscription plan page opens | Pass/Fail |
| NAV-007 | Verify Admin can navigate to Admin Dashboard | Admin must be logged in | 1. Click **Admin Dashboard** button | Admin dashboard loads successfully | Pass/Fail |
| NAV-008 | Verify navigation back using browser back button | None | 1. Navigate through 2–3 pages 2. Press browser back | User goes back to previous page correctly | Pass/Fail |
| NAV-009 | Verify broken links on header navigation | None | 1. Click each header link | All links open correct pages without 404 errors | Pass/Fail |
| NAV-010 | Verify footer links navigation (About, Contact, Privacy Policy) | None | 1. Scroll to footer 2. Click each link | Corresponding pages open | Pass/Fail |
| NAV-011 | Verify navigation for logout option | User must be logged in | 1. Click **Logout** from profile menu | User is logged out and redirected to login page | Pass/Fail |
| NAV-012 | Verify unauthorized users cannot navigate to protected pages | User not logged in | 1. Try accessing /profile, /jobs or /dashboard via URL | User gets redirected to Login page | Pass/Fail |
| NAV-013 | Verify user can refresh any page without app crash | None | 1. Open any page 2. Press browser refresh | Page reloads normally without errors | Pass/Fail |
| NAV-014 | Validate navigation performance | None | 1. Navigate between pages | Page should load within 1–3 seconds | Pass/Fail |
