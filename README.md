# EZ Check-in

QR code check-in app built for Google Developer Group (GDG) Medea events such as DevFest and I/O Extended. Organizers scan an attendee's QR code at the door and see their details instantly.

> Built in 2023 for live events. Archived; kept as a small, focused example.

## Features

- Camera QR scanning
- Attendee list loaded from JSON, with a details screen per attendee
- Works offline at the venue

## Tech stack

Flutter, `qr_code_scanner`, `path_provider`, Google Fonts.

The bundled `assets/attendees_list.json` contains placeholder data only.

## Run

```bash
flutter pub get
flutter run
```

## License

MIT, see [LICENSE](LICENSE).
