# Outfit-Recommendation

## Directory Structure

Getting Started
Follow these steps to set up the project locally:

Clone the repository:
```
git clone git@github.com:rmmfj/outfit-recommendation-app.git
cd outfit-recommendation-app
```
Install dependencies:
```
yarn
```
Set up environment variables: Create a .env.local file in the root directory and add your environment variables.

DATABASE_URL=your_database_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_database_anon_key
NEXT_PUBLIC_OPENAI_API_KEY=your_api_key
Run the development server:
```
yarn dev
```
Open your browser: Navigate to http://localhost:3000 to see the app in action.

```
/public
├── images
├── icons
/src
├── /app
│   ├── page.tsx (Home page)
│   ├── /upload
│   │   └── page.tsx (Upload photo page)
│   ├── /recommendation
│   │   └── page.tsx (Recommendation page)
│   ├── /register
│   │   └── page.tsx (User registration page)
│   ├── /login
│   │   └── page.tsx (User login page)
│   ├── /profile
│   │   └── page.tsx (User profile page)
│   ├── /history
│   │   └── page.tsx (Outfit history page)
│   └── /feedback
│       └── page.tsx (User feedback page)
├── /components
├── /styles
│   ├── globals.css
│   └── tailwind.css
├── /context
│   ├── auth-context.tsx
│   └── recommendation-context.tsx
├── /store
│   └── use-auth-store.ts (Zustand)
├── /hooks
│   ├── use-auth.ts
│   └── use-recommendations.ts
└── /utils
    ├── /supabase
    └── openai.ts
├── tailwind.config.js
├── next.config.js
├── tsconfig.json
├── package.json
└── README.md
```
