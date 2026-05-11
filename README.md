# VaxSync

VaxSync is a digital health management platform designed for local health departments to streamline vaccination programs, resident health records, and vaccine inventory. It is specifically built to support healthcare workers in rural areas with an offline-first approach, ensuring that service continues even without internet connectivity.

## 🚀 Key Features

- **Resident Management**: track vaccination history and health records for individuals across different barangays.
- **Inventory Tracking**: Real-time management of vaccine supplies, vial counts, and expiration dates.
- **Vaccination Sessions**: Plan and execute field vaccination sessions with direct beneficiary tracking.
- **Offline Mode**: Full offline data entry with automatic synchronization to the central database once internet is restored.
- **Automated Reporting**: Generate monthly reports and dashboards for health monitoring and compliance.

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) (React)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Database & Auth**: [Supabase](https://supabase.com/) (PostgreSQL)
- **UI Components**: [Radix UI](https://www.radix-ui.com/)

## 🏗️ Project Structure

- `vaxsync/app/`: Next.js App Router (Pages & API Routes)
- `vaxsync/components/`: Reusable UI components and feature-specific modules
- `vaxsync/hooks/`: Custom React hooks for authentication, offline state, and data fetching
- `vaxsync/lib/`: Core business logic, database wrappers, and synchronization managers

## 🛠️ Getting Started

1. **Clone the repository**
2. **Install dependencies**:
   ```bash
   cd vaxsync
   npm install
   ```
3. **Set up Environment Variables**: Create a `.env.local` with your Supabase credentials.
4. **Run the development server**:
   ```bash
   npm run dev
   ```

## 📄 License

This project is private and intended for local health department use.
