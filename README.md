# society subscription management app

This is a web app for managing monthly subscription fees for society residents. Residents can check what they owe, pay using simulated payment modes, and download payment receipts. Admins (society manager) can manage flats, create plans, generate monthly bills, track payments, and view charts/analytics.

## stack
- Frontend: Next.js (React), Tailwind CSS, Recharts (for dashboards), jspdf
- Backend: Node.js/Express
- Database: PostgreSQL

## how to run

### database
Import the database schema using the backup.sql file. Just run:
`psql -U postgres -d society_db -f ./backend/backup.sql`
(Make sure you create the `society_db` database first).

### backend
1. Go into the backend folder:
   `cd Society-Subscription-Management/backend`
2. Install dependencies:
   `npm install`
3. Create a `.env` file with these values:
   ```env
   PORT=5000
   PGUSER=postgres
   PGHOST=localhost
   PGDATABASE=society_db
   PGPASSWORD=your_password
   PGPORT=5432
   SESSION_SECRET=some_secret_string
   JWT_SECRET=another_secret_string
   FRONTEND_URL=http://localhost:3000
   ```
4. Run the server:
   `npm start`

### frontend
1. Go into the frontend folder:
   `cd Society-Subscription-Management/frontend`
2. Install dependencies:
   `npm install`
3. Create a `.env.local` file with:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:5000/api
   NEXTAUTH_SECRET=nextauth_secret_key
   NEXTAUTH_URL=http://localhost:3000
   ```
4. Start the next dev server:
   `npm run dev`

Open `http://localhost:3000` to access the application.
