# Outfit-Recommendation

## Directory Structure

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
