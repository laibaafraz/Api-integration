# Week 4: API Integration and Networking

A Flutter app that fetches and displays user data from [JSONPlaceholder](https://jsonplaceholder.typicode.com).

## Files
- `main.dart` — app entry point
- `users_screen.dart` — fetches API data and displays it

## Features
- Fetches users from `GET https://jsonplaceholder.typicode.com/users`
- Displays name and email in a ListView
- Shows a loading spinner while fetching
- Shows an error message with a Try Again button if the request fails

## How to Run
```bash
flutter pub get
flutter run
```

## Dependencies
```yaml
http: ^1.2.1
```
