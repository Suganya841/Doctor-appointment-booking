# CareSlot – Doctor Appointment Booking System (React + Vite)

## Run
```bash
npm install
npm run dev      # open the URL shown (usually http://localhost:5173)
npm run build    # production build in /dist
```

## Features
- Search doctors and filter by specialty
- Pick a date (only the doctor's working days, next 14 days) and a time slot
- Booked and past slots are disabled, so double booking is prevented
- Form validation (name, 10-digit mobile number, email)
- "My appointments" list with cancel
- Data is saved in the browser (localStorage)

## Structure
- `src/data.js` – doctors and time slots (edit to add doctors)
- `src/App.jsx` – all components (App, Appointments, BookingPanel)
- `src/styles.css` – styling
