# Recipe Discovery

A Flutter recipe browser with a bundled catalogue of **76 recipes**. Users can search by recipe title, filter the list, sort alphabetically, and open a detail screen with ingredients and step-by-step instructions.

## Features

- 76 recipe entries defined in the application source.
- Search by recipe title.
- Filter by vegetarian/non-vegetarian and food/drink.
- Sort by name ascending or descending.
- Recipe detail pages showing ingredients and preparation instructions.
- Flutter Material application with bundled image assets.

## Requirements

- Flutter SDK compatible with the Dart SDK constraint in `pubspec.yaml` (`>=2.12.0 <3.0.0`).
- Flutter-supported Android Studio/Xcode toolchains for the target platform.

## Run locally

```bash
git clone https://github.com/jayeshmepani/Recipe-App.git
cd Recipe-App
flutter pub get
flutter run
```

## Recipe data

The recipe list is currently embedded directly in `lib/main.dart`, with the `Recipe` model defined in `lib/models/recipe.dart`. The count of 76 refers to the current constructor entries in that source file; update this README whenever the list changes.

## Project structure

- `lib/main.dart` — app entry point and bundled recipe list
- `lib/models/recipe.dart` — recipe data model
- `lib/screens/recipe_list.dart` — search, filtering, sorting, and listing
- `lib/screens/recipe_details.dart` — recipe detail view
- `lib/widgets/recipe_card.dart` — recipe list card

## License

No license file was present in the inspected repository. Unless a license is added, normal copyright restrictions apply; contact the maintainer for reuse permission.
