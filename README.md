# SQLFlite-Databasese

Practical `sqflite` patterns — schema setup, queries and CRUD.

## Highlights

- Database creation and table definition shown step by step.
- Full CRUD operations against a local SQLite database.
- Provider state keeps screens in sync with the database.
- Live badge counts demonstrate querying and reacting to results.

## Tech Stack

| Concern | Choice |
|---|---|
| UI | Flutter, Material |
| Database | `sqflite`, `path_provider` |
| State management | `provider` |
| Utilities | `shared_preferences`, `badges` |

## Project Structure

```
lib/
- `database`
- `screen`
- `main.dart`
```

## Getting Started

### Prerequisites

- Flutter `>= 3.16` (Dart `>= 3.2`)

### Run

```bash
git clone https://github.com/developer-rahim/SQLFlite-Databasese.git
cd SQLFlite-Databasese
flutter pub get
flutter run
```

### Test

```bash
flutter test
flutter analyze
```

## Notes

A reference repository — the `database` folder holds the schema and query examples worth copying.

## License

Released under the MIT License.
