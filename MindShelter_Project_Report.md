
# MindShelter Project Report

## Introduction
MindShelter is a self-care and entertainment app designed with peaceful and complementary colors:
- **Main color**: Greenish tone (#078C8C)
- **Secondary color**: Light pink (#F2E2DF)

### Main Functions:
- **To-Do List**: Log, update, delete, and cross out tasks.
- **Mood Journal**: Write moods and receive inspirational quotes with random cute animal images.
- **Dynamic Background**: Changes each time the user returns to the home screen.
- **Beer Info**: Displays random beer information (using PUNK API).

## Features & Description
### Multiple Pages
- Home, Inspiration, To-Do List, Get a Beer.
- Modal Pages: Add New Task, Update Task.

### Services
- **Affirmation Service**: Fetches random inspirational quotes.
- **To-Do Service**: Manages task storage.
- **Beer API Service**: Fetches random beer information.

### Data Handling
- **APIs Used**:
  - [Quotable API](https://github.com/lukePeavey/quotable) for inspirational quotes.
  - [PUNK API](https://punkapi.com/) for beer information.

### Design & Components
- **Ionic Components Used**: `ion-list`, `ion-row`, `ion-col`, `ion-chip`, `ion-datetime`, `ion-modal`, `ion-button`, `ion-fab`, `ion-card`, `ion-checkbox`, `ion-textarea`.
- **Two-Way Data Binding**: Primarily used in the To-Do List feature.
- **Persistent Storage**: Implemented using Ionic Storage for storing tasks.
- **Design Goal**: Clean, peaceful, and centered layout with custom colors to enhance user experience.

## Bug Handling & Error Prevention
- **Beer API Image Handling**: Default image is displayed for beers without an image URL.
- **To-Do Task Validation**: Prevents adding tasks without a name.

## Reflection
- The To-Do app was built using tutorial series with personal adjustments, such as error handling and UI improvements.
- Faced challenges with launching the app initially and resolved by using `npm init –save` and modifying `package-lock.json`.
- Encountered issues with API CORS but solved them by switching to a compatible API.

## References
- [Ionic Framework Documentation](https://ionicframework.com/docs/)
- [Angular Services Example](https://github.com/dominiccarr/Angular_Services_Example)
- [Ionic Student Example](https://github.com/dominiccarr/IonicStudentExample)
