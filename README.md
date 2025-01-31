# SwiftUI+MVVM+DI Demo

Light | Dark
:-: | :-:
<video src='https://user-images.githubusercontent.com/48848704/192512927-b863b139-76b1-4874-94f8-9f89b4f4a0fb.mp4' width=90% controls autoplay> | <video src='https://user-images.githubusercontent.com/48848704/192513719-5282e547-2be8-4d3f-b51d-09de76d95b50.mp4' width=90% controls autoplay>

## Criteria

- SwiftUI
- MVVM architecture utilizing IoC.

## Functionality

- Fetching and parsing data from API.
- Listing Data.
- Searching.
- Search suggestions.
- Navigation to Details view.
- Dark mode.
- Unit tests.

## Design Decisions

- Dependency Manager:
  - Swift Package Manager

- Dependencies:
  - [Swinject](https://github.com/Swinject/Swinject): Dependency injection framework.
  - [Kingfisher](https://github.com/onevcat/Kingfisher): Downloading and caching images from the web.

## What could be improved

- Use Coordinator pattern for navigation.
- Use Repository pattern if local data storage is needed in the future.
