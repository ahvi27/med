# MediCare Patient Portal

A responsive medical appointment dashboard built with HTML, CSS, and JavaScript. Explore fictional doctors, schedule demo appointments, and manage upcoming visits.

## Features

- Search doctors by name or specialty
- Book demo appointments with a date and time
- Choose in-person or video visits
- Cancel saved appointments
- View upcoming visits in chronological order
- Prevent past bookings and duplicate time slots
- Switch between light and dark mode
- Save appointments and theme preferences in browser storage
- Responsive layout for mobile, tablet, and desktop

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage API
- Native HTML dialog

## Getting Started

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Choose a doctor and click **Book visit**.
4. Select a future date, time, and visit type.
5. Click **Save appointment**.

No installation, API keys, or build tools are required.

## Project Structure

```text
medicare-patient-portal/
├── index.html
└── README.md
```

All styles and JavaScript are included in `index.html`.

## Browser Storage

Appointments are stored under `medicare-appointments-v1`.
Theme preferences are stored under `medicare-theme-v1`.

Saved information stays in the current browser and does not sync across devices. Clearing browser storage removes it. Browser privacy settings may prevent saving.

## Customization

- Edit the `doctors` array to change the fictional providers.
- Update CSS variables in `:root` to customize the colors.
- Modify the appointment time options inside `appointmentTime`.
- Change the branding and page content directly in the HTML.

## Demo Limitations

This is a frontend portfolio project. Doctors are fictional, and appointments are not sent to a clinic.

There is no backend, authentication, real availability checking, or video consultation service. Times use the visitor’s local timezone.

Do not enter personal medical information. This website does not provide medical advice or emergency services.
