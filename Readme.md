# NFT Marketplace

## Purpose and goals of the application ##

The app helps users browse and buy NFT (Non-Fungible Token). The purchasing functionality is simulated using a mock server.

Application goals:

- viewing NFT collections;
- viewing and purchasing NFT (simulated);
- viewing the ratings of other users;
- view the user profile.

## Description of the application ##
- The application show a catalog of NFTs structured as collections.
- The user can view information about the collection catalog, the selected collection and the selected NFT.
- The user can add NFTs to favorites.
- The user can remove and add items to the cart and place the order (the purchase is simulated).
- User can view other users' rating and users' information.
- The user can view his profile, including information about favorites and NFTs owned by him.

Additional functionality is:
- localization
- dark theme
- onboarding screen
- an alert with an offer to rate the app in the AppStore
- custom launch screen

## Technology stack ##
- Swift, UIKit
- Architecture: MVP
- Code layout
- UITableView, UICollectionView, UITabBarController, WKWebView, UIPageController, UIScrollView
- URLSession
- UserDefaults
- Multithreading
- Swift Package Manager
- GCD
- YandexMetrica
- Kingfisher
- Localization
- Light/Dark theme

## Installation ##
Installation and launch via Xcode. Required dependencies are downloaded using Swift Package Manager.

Minimum system version is iOS 14.0.

## Recording screens demonstrating work ##

**Profile**

![Screenshot](ProfileEpicScreenCast.gif?raw=true)

**Catalog**

![Screenshot](CatalogEpicScreenCast.gif?raw=true)

**Cart**

![Screenshot](CartEpicScreenCast.gif?raw=true)

**Statistics**

![Screenshot](StatisticsEpicScreenCast.gif?raw=true)

## Links ##

[Design Figma](https://www.figma.com/file/k1LcgXHGTHIeiCv4XuPbND/FakeNFT-(YP)?node-id=96-5542&t=YdNbOI8EcqdYmDeg-0)
