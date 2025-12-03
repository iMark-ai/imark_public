# Privacy Policy for iMark

**Last Updated: December 2, 2025**

## Introduction

iMark ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our Chrome extension.

**By using iMark, you agree to the collection and use of information in accordance with this policy.**

---

## Information We Collect

### 1. Personal Information

When you use iMark, we collect the following personal information:

- **Email Address**: Collected via Google OAuth for account creation and authentication
- **Name**: Your display name from your Google account
- **Profile Picture**: Your Google profile picture (optional)

### 2. Authentication Data

- **JWT Tokens**: Stored locally in your browser to maintain your login session
- **OAuth Credentials**: Used only for authentication, not stored permanently

### 3. Web History Data

When you explicitly save a webpage to iMark:

- **Page URLs**: The web addresses of pages you choose to save
- **Page Titles**: The titles of saved webpages
- **Page Content**: Text content from saved pages for AI indexing
- **Images**: Images from saved pages for semantic understanding
- **Timestamps**: When you saved each page

### 4. Search Data

- **Search Queries**: The natural language queries you enter to find saved pages
- **Search Results**: Which results you click on (for improving relevance)

### 5. Usage Data

- **Number of Saved Pages**: To enforce tier limits (Free: 10, Basic: 1,000, Pro: Unlimited)
- **Subscription Status**: Your current plan and payment status
- **Extension Version**: For compatibility and support purposes

### 6. Technical Data

- **Browser Type**: Chrome, Edge, Brave, or Arc
- **Extension ID**: Unique identifier for your installation
- **Error Logs**: Technical errors for debugging (no personal content included)

---

## How We Use Your Information

We use the collected information for the following purposes:

### Core Functionality
- **Authentication**: Verify your identity and maintain login sessions
- **Bookmark Management**: Save, index, and retrieve your bookmarked pages
- **Semantic Search**: Process your queries and return relevant results
- **AI Processing**: Generate vector embeddings for semantic understanding

### Service Improvement
- **Performance Optimization**: Improve search accuracy and speed
- **Bug Fixes**: Identify and resolve technical issues
- **Feature Development**: Understand usage patterns to build better features

### Account Management
- **Subscription Management**: Process payments and manage tier limits
- **Usage Monitoring**: Enforce limits based on your subscription plan
- **Communications**: Send important service updates (rare, opt-out available)

---

## How We Store Your Information

### Data Storage

- **Local Storage**: Authentication tokens and user preferences are stored locally in your browser using Chrome's secure storage API
- **Cloud Database**: Saved pages, embeddings, and user data are stored in Supabase (PostgreSQL database)
- **Encryption**: All data is encrypted in transit using HTTPS/TLS
- **Data Centers**: Hosted on Google Cloud Platform (US region)

### Data Retention

- **Active Accounts**: Data retained as long as your account is active
- **Deleted Accounts**: All data permanently deleted within 30 days of account deletion
- **Inactive Accounts**: Accounts inactive for 2+ years may be deleted after email notification

---

## Data Sharing and Disclosure

### We DO NOT:
- ❌ Sell your data to third parties
- ❌ Share your browsing history with advertisers
- ❌ Use your data for purposes unrelated to iMark's core functionality
- ❌ Track your browsing activity outside of explicitly saved pages

### We MAY Share Data With:

#### Service Providers
- **Supabase**: Database hosting and user authentication
- **Google Cloud**: Backend API hosting
- **Stripe**: Payment processing (only subscription data, not browsing history)

These providers are contractually obligated to protect your data and use it only for providing services to iMark.

#### Legal Requirements
We may disclose your information if required by law or in response to valid legal requests (e.g., court orders, subpoenas).

---

## Your Rights and Choices

### Access and Control

You have the right to:

- **View Your Data**: See all pages you've saved and your account information
- **Export Your Data**: Download your saved bookmarks in JSON format
- **Delete Specific Items**: Remove individual saved pages
- **Delete Your Account**: Permanently delete all your data

### How to Exercise Your Rights

1. **In the Extension**: Go to Settings → Data Management
2. **Email Us**: Contact support@imark.ai with your request
3. **Response Time**: We'll respond within 30 days

### Opt-Out Options

- **Email Communications**: Unsubscribe link in all emails
- **Data Collection**: Delete your account to stop all data collection

---

## Cookies and Tracking

### What We Use

- **Session Cookies**: To maintain your login state
- **Local Storage**: For user preferences (theme, settings)

### What We DON'T Use

- ❌ Third-party advertising cookies
- ❌ Cross-site tracking
- ❌ Analytics cookies (we use privacy-focused analytics only)

---

## Children's Privacy

iMark is not intended for users under 13 years of age. We do not knowingly collect personal information from children under 13. If you believe we have collected information from a child under 13, please contact us immediately.

---

## International Users

iMark is operated from the United States. If you are located outside the U.S., please be aware that information we collect will be transferred to and processed in the United States.

### GDPR Compliance (EU Users)

If you are in the European Economic Area (EEA), you have additional rights under GDPR:

- **Right to Access**: Request a copy of your data
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of your data
- **Right to Portability**: Receive your data in a machine-readable format
- **Right to Object**: Object to certain data processing activities

**Legal Basis for Processing**: Consent (you explicitly save pages) and Contract (providing the service you signed up for).

---

## Security Measures

We implement industry-standard security measures:

- 🔒 **HTTPS/TLS Encryption**: All data transmitted securely
- 🔐 **Secure Authentication**: OAuth 2.0 with JWT tokens
- 🛡️ **Database Security**: Row-level security policies in Supabase
- 🔑 **Access Controls**: Limited employee access to user data
- 🔍 **Regular Audits**: Periodic security reviews and updates

**However**, no method of transmission over the internet is 100% secure. We cannot guarantee absolute security.

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:

1. Updating the "Last Updated" date at the top
2. Posting the new policy on this page
3. Sending an email notification for significant changes (if you've opted in)

**Your continued use of iMark after changes constitutes acceptance of the updated policy.**

---

## Third-Party Services

iMark integrates with the following third-party services:

### Google OAuth
- **Purpose**: User authentication
- **Data Shared**: Email, name, profile picture
- **Privacy Policy**: [Google Privacy Policy](https://policies.google.com/privacy)

### Supabase
- **Purpose**: Database and authentication
- **Data Shared**: All saved bookmarks and user data
- **Privacy Policy**: [Supabase Privacy Policy](https://supabase.com/privacy)

### Stripe (for paid plans)
- **Purpose**: Payment processing
- **Data Shared**: Email, subscription status (no browsing data)
- **Privacy Policy**: [Stripe Privacy Policy](https://stripe.com/privacy)

---

## Contact Us

If you have questions or concerns about this Privacy Policy:

- **Email**: privacy@imark.ai
- **Support**: support@imark.ai
- **GitHub**: [iMark Public Repository](https://github.com/yourusername/imark-public)

**Response Time**: We aim to respond within 48 hours.

---

## Summary (TL;DR)

✅ **We collect**: Pages you explicitly save, your email, and search queries  
✅ **We use it for**: Providing semantic search and managing your account  
✅ **We don't**: Sell your data, track your browsing, or share with advertisers  
✅ **You can**: View, export, or delete your data anytime  
✅ **Security**: HTTPS encryption, secure authentication, trusted providers  

---

**iMark is built with privacy in mind. Your data belongs to you.**

*Last Updated: December 2, 2025*
