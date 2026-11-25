# Vehicle Service and Maintenance Management System

A self-contained, role-based service desk demo for vehicle owners, workshop managers, and mechanics. The app is implemented in a single HTML file and runs in a modern browser without a build step or backend.

## Features

- **Customer accounts:** register, manage vehicles, book service slots, view job progress and invoices, approve estimates, and leave feedback.
- **Workshop management:** review bookings, assign mechanics, manage job cards and schedules, inspect vehicles, prepare estimates, and track service status.
- **Mechanic workspace:** view assigned jobs, update repair progress, record inspection findings, and use the spare-parts inventory.
- **Service records:** vehicle history, digital inspection checklists, labour and parts charges, invoices, taxes, discounts, payment status, warranty dates, and service reminders.
- **Workshop tools:** role-specific dashboards, notifications, reports, people and vehicle lists, and a database-style view.
- **Responsive interface:** works on desktop and mobile browsers.

## Run

No installation or build is required. You can open `index.html` directly in a browser. Alternatively, serve the project folder with Python:

```powershell
python -m http.server 8000
```

Keep the terminal window open while using the app, then visit <http://localhost:8000>.

## Demo accounts

| Role | Username | Password |
| --- | --- | --- |
| Admin | `admin` | `admin123` |
| Customer | `rahul` | `cust123` |
| Mechanic | `ravi` | `mech123` |

The demo also includes `meena` (customer, `cust123`) and `suresh` (mechanic, `mech123`). Demo data includes vehicles, service jobs, inspections, parts, invoices, and estimates.

## Data and limitations

The app seeds demo data on first use and saves changes in the browser's local storage. Data is local to the browser profile and device; it is not shared between users or browsers. Clearing the site's browser storage resets the demo. This is a frontend demonstration, not a production system: it has no server-side database, authentication, or data synchronization. Do not use real credentials or sensitive customer information.

## Project files

- `index.html` — complete application, including styles, interface, demo data, and browser-side logic.
- `seed.json` — accompanying sample data file.

## Credits

Project by Vatsal Kumar and Surya A.
