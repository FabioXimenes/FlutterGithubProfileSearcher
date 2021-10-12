# GithubProfileSearcher

[![codecov](https://codecov.io/gh/FabioXimenes/FlutterGithubProfileSearcher/branch/main/graph/badge.svg?token=LJLEKV2KNT)](https://codecov.io/gh/FabioXimenes/FlutterGithubProfileSearcher)

**Watch the final result on [Youtube](https://youtu.be/9nwZsw3qRlQ)**

## Functionalities

- Search github users
- Detailed information like name, localization, bio, avatar and email
- Bookmark profiles
- See bookmarked profiles even without connection (including profile image)

## Architecture and design

All the project was developed following **TDD** and **Clean Architecture**. The project has
a total of 63 unit tests and full coverage. The repository also contains a Github Action to execute all the tests upload coverage results to [codecov](https://about.codecov.io/) automatically when pushing to specific branches.


## Built With

- [mobx](https://pub.dev/packages/flutter_mobx)
- [get_it](https://pub.dev/packages/get_it)
- [shared_preferences](https://pub.dev/packages/shared_preferences)
- [http](https://pub.dev/packages/http)
- [data_connection_checker](https://pub.dev/packages/data_connection_checker)
- [mockito](https://pub.dev/packages/mockito)
- [equatable](https://pub.dev/packages/equatable)
- [cached_network_image](https://pub.dev/packages/cached_network_image)
- [dartz](https://pub.dev/packages/dartz)


## Get Started

1. Clone this repo

```sh
git clone https://github.com/FabioXimenes/FlutterGithubProfileSearcher
cd FlutterGithubProfileSearcher
```

2. Installing dependencies

```sh
flutter pub get
```

3. Running the project

```sh
flutter pub run build_runner build --delete-conflicting-outputs
flutter run
```