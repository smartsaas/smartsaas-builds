# SmartSaaS Change Log
---

#### 1.0.8701 (2025-12-09)

##### Chores

* **config:**  Update .gitignore to include APK files and modify font family settings in tamagui.config.json to use 'System' instead of 'Inter' and 'Outfit' (87fed551)

##### New Features

* **ui:**  Updated styles and layout adjustments across various components, added new features for improved user interaction, and integrated expo-iap for in-app purchases. (1547d807)
* **navigation:**  Enhanced navigation structure and updated various components for improved user experience (a1346657)
* **messaging:**  Corrected and enhanced messaging features as well as a number of other fixes (137e0acd)
* **actions:**
  *  Connected actions to datasets (4af92986)
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **flows:**
  *  enhanced flow additions (07e58a3d)
  *  Added additonal flows (fa03afbc)
* **scraper:**  Added AI Scraper in knowledge base (ffddd2f4)
* **Flows:**
  *  Added flow building features (7f247723)
  *  AI voice flows (70971af0)
* **Academy:**  Latest changes with AI support, academy integration and visual updates (d6289488)
* **React19:**  Updated major version of React (eb5fe314)
* **AI:**
  *  AI actions (3389eda2)
  *  Added multiple AI features (de677c73)
  *  Tying in AI features from back-end (6f0b5f27)
* **stable:**  Updated deps (9baab01f)
* **hierarchy:**
  *  Corrected hierarchy breakage in academy screen (d4c1a53f)
  *  Corrected functionality of hierarchy and made several UI changes (52c85cdb)
* **affiliates:**
  *  All affiliate functionality corrected and added to Login Screen (9db29268)
  *  Added affiliate tracking and payouts (1e253e87)
* **projects:**
  *  Added comprehensive user management (bedb7b1e)
  *  Corrected project layouts (805735ba)
  * Modernised and refined projects (460b3928)
* **Meetings:**  New meetings (14ef7aa8)
* **UI:**
  *  Improved UI (c2cacdf3)
  *  Update to new app version (c7368973)
  *  Improved visual components across app (3b07b1e0)
  *  Misc UI fixes (894940ea)
* **pagination:**  Added pagination to all routes (67420986)
* **social:**
  *  Added social media post designer (dc599146)
  *  Added AI features to social feed (f13ebe33)
* **Login:**  Various fixes to login screen (19286562)
* **reports:**  Implemented Reports Dashboard and connected to back-end routes (25a02737)
* **New Features:**  Added several new features including utilities and hierarchy handling (7dc4205f)
* **ProductionMode:**  Latest changes to finalise for production readiness (d3e10565)
* **visuals:**
  *  New changes made to visual uphaul (fa86cb5d)
  *   Changes to menu and layout (a370acef)
* **whatsapp:**  Added whatsapp webhooks (159924e4)
* **community:**  Added community screens (2f5f5759)
* **doc-editor:**  Document editor upgraded (3f799e5c)
* **schema:**  Corrected schema handling (a645487c)
* **service-worker:**  Added service-worker to auto update packages (4e670f09)
* **bubbles:** New bubble screen to show links between data (b09449b6)
* **CRM:**
  *  Added new product and CRM screens (b1ed44a1)
  *  Added new product and CRM screens (7ccc0c35)
* **upload:**
  *  New changes added to upload supporting xlsx, xls (f5ac45fa)
  *  New changes added to upload supporting xlsx, xls (14f1e0a3)
* **stats:**  More stat geatures added (a738b3c4)
* **integrations:**
  *  Added integration components (f6f9ef9f)
  * Added social integrations, corrected CSS serving (6c4d6c9d)
* **version:**  Version change implemented (175babfb)
* **slack:**  Added slack integration (4ee9f49b)
* **web:**  Corrected and replaced web forms (07ef959a)
* **mobile:**
  *  Corrections to billing and metered data retrieval (4e086ec0)
  *  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **data-move:** Added move data feature and Sinhala language (a7c63455)
* **staging:**
  * corrected staging changes (9f52046f)
  * Implemented staging site to speed-up development (c616fd31)
* **misc:**  Changes (138dcc87)
* **payments:** Various payment fixes (df937566)
* **various:**  Various fixes, changes and features (e800882c)
* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **expo-54:**  Upgraded to Expo 54 for final app (e377eb3d)
* **UI:**  Improvements to UI and metering (3afb5530)
* **deps:**
  *  Dependency issues corrected (b28affa5)
  *  Removed bad import (7e9194ac)
* **missing deps:**  Corrected missing dep @tamagui/portal (f685c0ef)
* **optimisation:**  Corrected Tamagui import of Social Media Scheduler (69decefe)
* **dependency:**  Removed false momentjs dependency (3547b7e4)
* **layout:**
  *  Corrected mobile responsiveness on web app (27dfc69c)
  *  New layout fixes and minor version update (f1c74790)
* **api:**  Mobile resolved (14d05352)
* **ai-help:**  AI Help modal fixed (323e9b41)
* **Linking:**  Linking Configuration (cf65b64f)
* **projects:**  Corrected bad rendering in projects (6e59d401)
* **editor:**  Editor changes made (f91c7e78)
* **env-vars:**  Corrected model (3589cc33)
* **emails:**  Corrected email editor (585a1376)
* **performance:**  Enhanced performance by seperating auth stack from dash stack (8b3f2e46)
* **css:**
  * Remove global transition values that were causing slow-down (6f1a3d1a)
  *  Added new CSS for data grid (7078fad9)
* **datahandler:**  Corrected drop downs (430982a4)
* **visuals and editor:**  Added new editor and visual fixes (669d2c14)
* **web-output:**  Corrected web output (9a15ab67)
* **output:**  Changed web output back to dist (51547c24)
* **CSS:**  CSS corrected (7ad4903b)
* **menu:**  Visual changes for menu and messaging implemented, emails connected and material UI applied to overall (a7cb626b)
* **remove-paper:**  Completely removed react-native-paper and made changes to css serve (45e5c6d5)
* **rn-paper:**  Remove UI library r-n-paper (7ae79803)
* **visuals:**  Corrected some visual aspects (6892cba8)
* **stripe:**  Crash on iPad and tablets due to outdated stripe dependency corrected (01ee949b)
* **visual:**  Visual changes applied for Foldable Android devices (84397b25)
* **MessageUserList:**  Code correction and case correction (1d67e992)
* **remove:**  Removed MessageUserList (e485ec09)
* **second-menu:**  Remove unecessary second menu rendering (1ed01188)
* **misc:**  Misc fixes (7471343e)
* **actions:**  Action handler visual issues  rectified (bc82bf56)
* **drag:**  User components almost solved, just need to correct translation space multiplication (63eecec9)
* **socials:**
  *  Social feeds altered and implemented sponsored products (597bcf21)
  *  Social integration begins (1870ccae)
* **mobile:**  Corrected changes to mobile app (ef05be25)
* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into staging (c6ceaf74)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

