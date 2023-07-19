# flutter_infinite_list_bloc
Project structure:
├── lib
|   ├── posts
│   │   ├── bloc
│   │   │   └── post_bloc.dart
|   |   |   └── post_event.dart
|   |   |   └── post_state.dart
|   |   └── models
|   |   |   └── models.dart
|   |   |   └── post.dart
│   │   └── view
│   │   |   ├── posts_page.dart
│   │   |   └── posts_list.dart
|   |   |   └── view.dart
|   |   └── widgets
|   |   |   └── bottom_loader.dart
|   |   |   └── post_list_item.dart
|   |   |   └── widgets.dart
│   │   ├── posts.dart
│   ├── app.dart
│   ├── simple_bloc_observer.dart
│   └── main.dart
├── pubspec.lock
├── pubspec.yaml

Project REST API for data use: https://jsonplaceholder.typicode.com/posts?_start=0&_limit=2
