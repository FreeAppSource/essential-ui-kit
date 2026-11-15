# Essential UI Kit

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **Syncfusion** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `essential-ui-kit-for-xamarin.sketch` by **Syncfusion**: one route per artboard, with the artboard's layout, colours, images and text.

![Essential UI Kit screens](./showcase.jpg)

## 📱 Screens (48 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **Onboarding Page** · start screen | `src/app/onboarding-page.jsx` | 375 × 667 | 1 |
| 2 | **About Us App Page** | `src/app/about-us-app-page.jsx` | 375 × 667 | 2 |
| 3 | **About Us Image Page** | `src/app/about-us-image-page.jsx` | 375 × 1154 | 4 |
| 4 | **About Us Page** | `src/app/about-us-page.jsx` | 375 × 667 | 4 |
| 5 | **Article Bookmark Page** | `src/app/article-bookmark-page.jsx` | 375 × 667 | 5 |
| 6 | **Article Burger Menu Expand Page** | `src/app/article-burger-menu-expand-page.jsx` | 375 × 667 | 6 |
| 7 | **Chat Home Page** | `src/app/chat-home-page.jsx` | 375 × 667 | 2 |
| 8 | **Article Interests Page** | `src/app/article-interests-page.jsx` | 375 × 667 | 5 |
| 9 | **Article Profile Page** | `src/app/article-profile-page.jsx` | 375 × 667 | 5 |
| 10 | **Article Burger Menu Page** | `src/app/article-burger-menu-page.jsx` | 375 × 667 | 2 |
| 11 | **Chat Multiselection Page** | `src/app/chat-multiselection-page.jsx` | 375 × 667 | 3 |
| 12 | **Article List Page** | `src/app/article-list-page.jsx` | 375 × 667 | 6 |
| 13 | **Bottom Navigation Album Page** | `src/app/bottom-navigation-album-page.jsx` | 375 × 667 | 7 |
| 14 | **Article Detail Page** | `src/app/article-detail-page.jsx` | 375 × 1371 | 3 |
| 15 | **Chat Page** | `src/app/chat-page.jsx` | 375 × 667 | 2 |
| 16 | **Bottom Navigation Photos Page** | `src/app/bottom-navigation-photos-page.jsx` | 375 × 667 | 2 |
| 17 | **Article Grid Page** | `src/app/article-grid-page.jsx` | 375 × 871 | 6 |
| 18 | **Chat Profile Page** | `src/app/chat-profile-page.jsx` | 375 × 667 | 2 |
| 19 | **Bottom Navigation Setting Page** | `src/app/bottom-navigation-setting-page.jsx` | 375 × 667 | 4 |
| 20 | **Chat Profile Page_2** | `src/app/chat-profile-page-2.jsx` | 375 × 667 | 3 |
| 21 | **Cart Page** | `src/app/cart-page.jsx` | 375 × 794 | 3 |
| 22 | **Chat Swipe Page** | `src/app/chat-swipe-page.jsx` | 375 × 667 | 3 |
| 23 | **Catalog Page List** | `src/app/catalog-page-list.jsx` | 375 × 667 | 5 |
| 24 | **Checkout Page** | `src/app/checkout-page.jsx` | 375 × 1064 | 5 |
| 25 | **Catalog Page Tile** | `src/app/catalog-page-tile.jsx` | 375 × 667 | 5 |
| 26 | **Filter Page** | `src/app/filter-page.jsx` | 375 × 667 | 2 |
| 27 | **Contact Us Page** | `src/app/contact-us-page.jsx` | 375 × 700 | 2 |
| 28 | **Category Page List** | `src/app/category-page-list.jsx` | 375 × 667 | 4 |
| 29 | **Forgot Password Page** | `src/app/forgot-password-page.jsx` | 375 × 667 | 3 |
| 30 | **Category Page Tile** | `src/app/category-page-tile.jsx` | 375 × 667 | 4 |
| 31 | **Login Page** | `src/app/login-page.jsx` | 375 × 667 | 3 |
| 32 | **Sign Up Page** | `src/app/sign-up-page.jsx` | 375 × 667 | 3 |
| 33 | **Login Page Light** | `src/app/login-page-light.jsx` | 375 × 667 | 5 |
| 34 | **Sort Page** | `src/app/sort-page.jsx` | 375 × 667 | 2 |
| 35 | **Navigation List Card Page** | `src/app/navigation-list-card-page.jsx` | 375 × 688 | 3 |
| 36 | **Tablet Product Detail Page** | `src/app/tablet-product-detail-page.jsx` | 768 × 1382 | 2 |
| 37 | **Navigation Tile Card Page** | `src/app/navigation-tile-card-page.jsx` | 375 × 930 | 3 |
| 38 | **Navigation Tile Card Page_2** | `src/app/navigation-tile-card-page-2.jsx` | 375 × 930 | 3 |
| 39 | **Onboarding Page Gradient** | `src/app/onboarding-page-gradient.jsx` | 375 × 667 | 2 |
| 40 | **Onboarding Page_2** | `src/app/onboarding-page-2.jsx` | 375 × 667 | 2 |
| 41 | **Onboarding Page_2 Gradient** | `src/app/onboarding-page-2-gradient.jsx` | 375 × 667 | 2 |
| 42 | **Onboarding Page_3** | `src/app/onboarding-page-3.jsx` | 375 × 667 | 2 |
| 43 | **Onboarding Page_3 Gradient** | `src/app/onboarding-page-3-gradient.jsx` | 375 × 667 | 2 |
| 44 | **Product Detail Page** | `src/app/product-detail-page.jsx` | 375 × 1374 | 2 |
| 45 | **Reset Password Page** | `src/app/reset-password-page.jsx` | 375 × 667 | 3 |
| 46 | **Review Page** | `src/app/review-page.jsx` | 375 × 694 | 2 |
| 47 | **Review Page_1** | `src/app/review-page-1.jsx` | 375 × 667 | 5 |
| 48 | **Review Page_2** | `src/app/review-page-2.jsx` | 375 × 667 | 4 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (Inter, Montserrat), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/essential-ui-kit> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **UI Kit for Xamarin.Forms** design by **Syncfusion**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [Syncfusion](https://www.sketchappsources.com/contributor/syncfusion) |
| Original design | [UI Kit for Xamarin.Forms](https://github.com/syncfusion/essential-ui-kit-for-xamarin.forms) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4090-essential-ui-kit-for-xamarin-forms-sketch-freebie-resource.html) |
| Twitter | <https://twitter.com/Syncfusion> |
| Original file | `essential-ui-kit-for-xamarin.sketch` |
| License / usage | MIT License (the designer's official GitHub repository, syncfusion/essential-ui-kit-for-xamarin.forms). Commercial use allowed; keep the licence notice. |

**Attribution:**

> UI design: "UI Kit for Xamarin.Forms" by Syncfusion (https://github.com/syncfusion/essential-ui-kit-for-xamarin.forms), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4090-essential-ui-kit-for-xamarin-forms-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
