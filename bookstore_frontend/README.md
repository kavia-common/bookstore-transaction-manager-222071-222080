# bookstore_frontend

Mobile Flutter app for managing bookstore transactions.

Features:
- Ocean Professional theme (blue primary with amber accents)
- Bottom navigation: Dashboard, Add Transaction, Profile
- Login flow using JWT stored in shared_preferences
- API client using BASE_URL from .env and Authorization: Bearer <token>
- Providers (Provider package) for auth and transactions
- Create, edit, delete transactions
- Dashboard with total summary and recent list
- Profile with logout

Getting Started:
1) Copy .env.example to .env and set BASE_URL to your backend FastAPI URL:
   BASE_URL=http://localhost:3001

2) Install dependencies:
   flutter pub get

3) Run:
   flutter run

Notes:
- The app title is "Bookstore Manager".
- Tests updated to reflect the new title and login screen.
