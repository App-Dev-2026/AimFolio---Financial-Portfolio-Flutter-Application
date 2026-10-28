# 📈 📊 AimFolio - Financial Portfolio Flutter Application
### Main Objective
The goal of this application is to provide users with a simple way to manage their stock and ETF investments. Users can view their portfolio performance on a dashboard, manually manage their holdings and purchase prices, and use the latest available market prices to calculate estimated portfolio values and profit or loss.

---

## 📱 Core Architecture & UI Flow

*   🚀 **Animated Splash Screen:** Elegant, automated launch screen serving as a gatekeeper for authentication status on startup.
*   📑 **Auth Portal Tab Bar View:** Advanced sliding tab headers built on the landing portal to seamlessly toggle between layouts:
    1. **Sign In Tab View:** Secure interface layout for existing users to log into their profile.
    2. **Sign Up Tab View:** User registration layout to initialize a fresh portfolio account.
    3. **Forgot Password Screen:** Dedicated recovery view for sending secure password reset links via email.
*   🧭 **Navigation & Core Layout:**
    *   **Persistent Bottom Navigation Bar:** Clean menu widget to quickly toggle between primary views like Holdings and Profiles.
    *   **Smooth Page Routing:** Seamless transitions moving users from the main Dashboard over to the comprehensive Asset Details page.
    *   **Scrollable List View:** Efficient scrolling containers engineered to dynamically render infinite asset rows.
    *   **Contextual Action Controls:** Integrated 3-dot pop-up menu buttons or elevated buttons nested inside asset cards, providing compact shortcuts to Add, Modify, or Delete holdings.

---

## 🔒 Backend & Data Integration

*   🔥 **Firebase Authentication:** Handles secure backend token management and verifies live user registration and sign-in status.
*   🛡️ **Firestore Security Rules:** Server-side privacy filters enforcing strict user isolation by validating unique authenticated request UIDs to prevent data leakage.
*   📈 **Alpaca REST API Integration:** Robust external network infrastructure linking the client app directly to live financial data servers over HTTP.
*   🔄 **Asynchronous JSON Data Fetching:** Complex decoding pipelines parsing nested JSON responses from Alpaca endpoints directly into local data models.
*   💾 **Cloud Database CRUD:** Asynchronous data layer methods executing full Create, Read, Update, and Delete commands against cloud database tables.
*   💬 **Reactive App SnackBar Notifications:** Built-in alert pop-ups triggering real-time feedback confirmations upon successful database operations.

---

## 🛠️ Getting Started

### Prerequisites
*   A Firebase project configured for Authentication and Firestore.
*   An Alpaca API key for fetching live market data.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/App-Dev-2026/AimFolio---Financial-Portfolio-Flutter-Application.git
   ```
2. Set up your environment variables/configuration files for Firebase and Alpaca API credentials.
3. Run the application on your target platform or emulator.
   
[🖥️ View AimFolio PowerPoint Presentation](https://eduvaniercollegeqc-my.sharepoint.com/:p:/r/personal/6117227_edu_vaniercollege_qc_ca1/Documents/ApDev/AimFolio.pptx?d=w59d91d5bdc7f4a248d3f43a33e09a78b&csf=1&web=1&e=4KJnMc)

[📐View Figma Prototype](https://www.figma.com/proto/lXJj9ujfOxjcJbLhWbpQog/Onboarding--Login---Register---App-Ui--Community---Copy-?node-id=807-69&p=f&t=CcsDeaHltXXkQMzo-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2&show-proto-sidebar=1)

