# OS Encyclopedia

A comprehensive, full-stack web application for exploring and managing operating systems and their versions. Built with Next.js 14+, TypeScript, TailwindCSS, Framer Motion, and Supabase.

## 🚀 Features

- **Modern Tech Stack**: Next.js 14+ with App Router, TypeScript, and TailwindCSS
- **Authentication**: Supabase Auth with protected routes and middleware
- **Database**: Supabase PostgreSQL with real-time capabilities
- **UI/UX**: Beautiful, responsive design with dark mode support
- **Animations**: Smooth animations using Framer Motion
- **Form Handling**: React Hook Form with Zod validation
- **Search & Filtering**: Advanced search and filtering capabilities
- **Version Management**: Comprehensive OS version tracking
- **Responsive Design**: Mobile-first approach with TailwindCSS

## 🛠️ Tech Stack

- **Framework**: Next.js 14+ (App Router)
- **Language**: TypeScript
- **Styling**: TailwindCSS
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **Animations**: Framer Motion
- **Forms**: React Hook Form + Zod
- **Icons**: Lucide React
- **UI Components**: Custom design system with Radix UI primitives
- **Deployment**: Vercel-ready

## 📁 Project Structure

```
/os-encyclopedia
├── app/                    # Next.js App Router pages
│   ├── layout.tsx         # Root layout with providers
│   ├── page.tsx           # Home page
│   ├── os/                # OS-related pages
│   │   ├── page.tsx       # OS listing
│   │   ├── new/           # Add new OS
│   │   └── [slug]/        # Dynamic OS pages
│   ├── dashboard/         # Protected dashboard
│   └── auth/              # Authentication pages
├── components/            # Reusable components
│   ├── ui/               # Base UI components
│   ├── shared/           # Layout components
│   ├── animations/       # Framer Motion wrappers
│   ├── cards/            # Card components
│   └── forms/            # Form components
├── lib/                  # Utility libraries
│   ├── supabase/         # Supabase configuration
│   ├── os.ts             # OS-related functions
│   └── auth.ts           # Authentication helpers
├── types/                # TypeScript type definitions
├── utils/                # Utility functions
├── constants/            # App constants and metadata
└── middleware.ts         # Route protection
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Supabase account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/minamrahman727/os-encyclopedia.git
   cd os-encyclopedia
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Set up Supabase**
   - Create a new Supabase project
   - Run the database schema (see `db/schema.sql`)
   - Configure authentication settings
   - Set up Row Level Security (RLS) policies

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🗄️ Database Schema

The application uses the following main tables:

- `operating_systems`: Core OS information
- `versions`: OS version details
- `users`: User accounts and profiles
- `user_profiles`: Extended user information

## 🔐 Authentication

The app uses Supabase Auth with:
- Email/password authentication
- Protected routes via middleware
- Role-based access control
- Session management

## 🎨 Design System

Built with a custom design system featuring:
- Consistent color palette with dark mode support
- Typography scale
- Spacing system
- Component variants
- Animation patterns

## 📱 Responsive Design

The application is fully responsive with:
- Mobile-first approach
- Breakpoint system
- Flexible layouts
- Touch-friendly interactions

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy!

### Other Platforms

The app can be deployed to any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing framework
- [Supabase](https://supabase.com/) for the backend services
- [TailwindCSS](https://tailwindcss.com/) for the styling system
- [Framer Motion](https://www.framer.com/motion/) for animations
- [Lucide](https://lucide.dev/) for the beautiful icons

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Check the documentation
- Join our community discussions

---

Built with ❤️ by the Team ZEX
