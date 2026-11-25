# Vehicle Service and Maintenance Management System

A self-contained browser app for managing vehicle service operations. It includes demo users and stores changes in the browser's local storage.

## Run

Open `index.html` in a browser, or serve this folder locally:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Demo accounts

| Role | Username | Password |
| --- | --- | --- |
| Admin | `admin` | `admin123` |
| Customer | `rahul` | `cust123` |
| Mechanic | `ravi` | `mech123` |

The app runs entirely in the browser. Data is saved to local storage on the device and browser profile in use.
