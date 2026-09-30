rakshakseva/
├── README.md                 # Executive badges, Indian Good Samaritan law, architecture, demo walkthrough
├── package.json              # Monorepo configuration
├── docker-compose.yml        # Full-stack containerized orchestration
├── render.yaml               # 1-Click Render backend deployment blueprint
├── .env.example              # Environment variables template
├── docs/                     # Specifications, Security, and Architecture Decision Records
│   ├── SPEC.md
│   ├── SECURITY.md
│   └── DECISIONS.md
├── database/                 # PostgreSQL / Supabase schema & migrations
│   ├── migrations/
│   │   ├── 001_initial_schema.sql
│   │   ├── 002_rls_policies.sql
│   │   └── 003_functions_and_triggers.sql
│   └── seed/seed.sql
├── backend/                  # Node.js + Express + TypeScript REST API
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── tests/
│   ├── Dockerfile
│   └── tsconfig.json
└── web/                      # React 18 + Vite + Tailwind CSS PWA
    ├── src/
    │   ├── components/       # Lock-Screen Wallpaper Generator, QR Scanner, Emergency Card
    │   ├── pages/            # Dashboard, Bystander Redacted View, Crash Engine, Rewards, Admin
    │   ├── context/          # Wake-Lock Ride Mode & Motion Sensors
    │   └── tests/
    ├── vercel.json           # 1-Click Vercel frontend deployment
    └── vite.config.ts
