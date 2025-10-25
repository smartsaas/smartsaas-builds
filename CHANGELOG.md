# SmartSaaS Change Log
---

#### 1.0.8601 (2025-10-25)

##### New Features

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
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
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

#### 1.0.3101 (2025-09-03)

##### New Features

* **visuals:**
  *  New changes made to visual uphaul (fa86cb5d)
  *   Changes to menu and layout (a370acef)
* **whatsapp:**  Added whatsapp webhooks (159924e4)
* **community:**  Added community screens (2f5f5759)
* **doc-editor:**  Document editor upgraded (3f799e5c)
* **schema:**  Corrected schema handling (a645487c)
* **service-worker:**  Added service-worker to auto update packages (4e670f09)
* **bubbles:** New bubble screen to show links between data (b09449b6)
* **AI:**
  *  Added multiple AI features (de677c73)
  *  Tying in AI features from back-end (6f0b5f27)
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
* **affiliates:**  Added affiliate tracking and payouts (1e253e87)
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
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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
* **layout:**  New layout fixes and minor version update (f1c74790)
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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.1003 (2025-05-13)

##### New Features

* **misc:**  Changes (138dcc87)
* **payments:** Various payment fixes (df937566)
* **staging:** Implemented staging site to speed-up development (c616fd31)
* **various:**  Various fixes, changes and features (e800882c)
* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.1003 (2025-05-13)

##### New Features

* **payments:** Various payment fixes (df937566)
* **staging:** Implemented staging site to speed-up development (c616fd31)
* **various:**  Various fixes, changes and features (e800882c)
* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.999 (2025-04-29)

##### New Features

* **various:**  Various fixes, changes and features (e800882c)
* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.999 (2025-04-22)

##### New Features

* **various:**  Various fixes, changes and features (e800882c)
* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.986 (2025-03-26)

##### New Features

* **company-switch:**  Added Company switch functionality (5e9242ce)
* **calendars:**  Added SmartSaaS calendar functionality and misc fixes on web (5bce7489)
* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.985 (2025-03-12)

##### New Features

* **users:**  User screen rectified and misc bugs and issues solved (c14af154)
* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.983 (2025-03-12)

##### New Features

* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.981 (2025-03-10)

##### New Features

* **flows:**  Added additonal flows (fa03afbc)
* **calls:** Begin implementing call features for AI based calling (9080a448)
* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.703 (2025-02-06)

##### New Features

* **meetings:**  Tons of new features added with AI functionality including meetings transcription, calendar management and social media creation (0ef59037)
* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.703 (2025-02-06)

##### New Features

* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.8 (2025-01-16)

##### New Features

* **Backend:**  Backend QR based routes added (12f57c84)
* **actions:**
  *  Added actions and actoin editor with fixes for new QR code actions and adjustments of visuals (f4ad0e8b)
  * Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.8 (2025-01-10)

##### New Features

* **actions:** Chain actions and calendar QR bookings implemented (7564d311)
* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.8 (2025-01-05)

##### New Features

* **scheduler:**  Added scheduling and data attachment functionality (0a0aa5aa)
* **Calendars:** Added adn corrected calendar functionality (d718182f)
* **products:** Product screen patched and corrected with notes history (e8a6a635)
* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

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

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.621 (2024-12-19)

##### New Features

* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **mobile:**  Corrected changes to mobile app (ef05be25)
* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.621 (2024-12-19)

##### New Features

* **video tutorials:**  Implemented video tutorials for easy learning of different modules (c6e6c175)
* **mobile:**  Unified mobile features in preparation for iOS release with in-app subs (9d349efe)
* **update:**  Release change (29cba283)
* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **mobile:**  Corrected changes to mobile app (ef05be25)
* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (43bd932c)
* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)
* **modal:**  TC modal patched responsivity (33f9fca8)

#### 1.0.620 (2024-12-04)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-11-13)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-11-13)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-10-21)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-10-07)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-10-07)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-10-06)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-10-01)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-09-26)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.620 (2024-09-24)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-14)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-14)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-14)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-09)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

### 1.1.0 (2024-09-06)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **major:**  Lots of features corrected or improved (06d8786b)
* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-05)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-09-02)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.612 (2024-08-26)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.609 (2024-08-23)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.609 (2024-08-20)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.608 (2024-08-17)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-08-17)

##### New Features

* **ai:**  New AI features appended (14c1868d)
* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **modal:**  Remove always true var from visible state (778622fb)
* **Modal:**  Patched TC Modal to fit in with responsivity (a486c8e0)
* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver into Expo-50 (7a5c9d6f)

#### 1.0.605 (2024-07-02)

##### New Features

* **social:**  Added AI features to social feed (f13ebe33)
* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

#### 1.0.605 (2024-06-20)

##### New Features

* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **additional:**  Other features added (84286e3b)
* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

#### 1.0.604 (2024-06-13)

##### New Features

* **networking:**  Added GMaps and local networks, feat(emails): Corrected and added remaming functionality for Gmail, feat(calendars): Revamped calendar component to be more fluid and consistent, fix(contexts): Increased performance by removing unecessary memoization, fix(UI): added several improvements to user interface and decreased performance overheads, breaking(state): some global state changes were made which may require refresh of app (133d2252)
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **changelog:**  Revert changes (46044809)
* **logs:**  Removed logs (97f13450)
* **socials:**  Social integration begins (1870ccae)

#### 1.0.602 (2024-06-13)

##### New Features

* **networking:** added GMaps and local networks
* **emails:** corrected and added renaming functionality for Gmail
* **calendars:** revamped calendar component to be more fluid and consistent
* **backend:**  Server email functionality (5ccaafab)
* **campaigns:**  Added campaign features (2fe337fd)

##### Bug Fixes

* **contexts:** increased performance by removing unnecessary memoization
* **UI:** added several improvements to user interface and decreased performance overheads
* **socials:**  Social integration begins (1870ccae)

##### BREAKING
* **state:** some global state changes were made which may require a refresh of the app (133d2252)

#### 1.0.593 (2024-05-06)

##### New Features

* **email-builder:**  Email builder integrated (8608b7b3)
* **version:**  Version upgrade with data uploading, project management routes and email builder, sales campaign (70593c10)
* **deploy:**  One click deployment added to production and staging (7819acbb)
* **email:**  Email features integrated (ee38f7df)
* **projects:**  Draggable timeline in Gantt Chart feat(Calendar): Completed import of calendar from mobile feat(Data): Changed import flow and data screens (c458fad6)

##### Bug Fixes

* **mail:**  more changes (cbaab1b1)
* **projects:**  Attached all project routes and data routes and others (a0c7a245)

##### Other Changes

* **state:**  Converted state to use Dispatch instead of directly importing store (ca24e85e)
* **google:**  Corrected authentication mechanism and corrected google web analytics -m feat(projects): Added ability to have failstate on tasks to easily track tasks that can also fail -m feat(emails): Email features now fully integrated into app along with refresh handling -m fix(forms): Forms performance enhanced greatly -m fix(types): Added additional types to support etended functionality -m fix(sales): Corrected layouts for sales dashboard view (376277d8)
* storybook (cf3edcb7)

#### 1.0.592 (2024-05-01)

##### New Features

* **version:**  Version upgrade with data uploading, project management routes and email builder, sales campaign (70593c10)
* **deploy:**  One click deployment added to production and staging (7819acbb)
* **email:**  Email features integrated (ee38f7df)
* **projects:**  Draggable timeline in Gantt Chart feat(Calendar): Completed import of calendar from mobile feat(Data): Changed import flow and data screens (c458fad6)

##### Bug Fixes

* **mail:**  more changes (cbaab1b1)
* **projects:**  Attached all project routes and data routes and others (a0c7a245)

##### Other Changes

* **google:**  Corrected authentication mechanism and corrected google web analytics -m feat(projects): Added ability to have failstate on tasks to easily track tasks that can also fail -m feat(emails): Email features now fully integrated into app along with refresh handling -m fix(forms): Forms performance enhanced greatly -m fix(types): Added additional types to support etended functionality -m fix(sales): Corrected layouts for sales dashboard view (376277d8)
* storybook (cf3edcb7)

#### 1.0.592 (2024-05-01)

##### New Features

* **version:**  Version upgrade with data uploading, project management routes and email builder, sales campaign (70593c10)
* **deploy:**  One click deployment added to production and staging (7819acbb)
* **email:**  Email features integrated (ee38f7df)
* **projects:**  Draggable timeline in Gantt Chart feat(Calendar): Completed import of calendar from mobile feat(Data): Changed import flow and data screens (c458fad6)

##### Bug Fixes

* **mail:**  more changes (cbaab1b1)
* **projects:**  Attached all project routes and data routes and others (a0c7a245)

##### Other Changes

* **google:**  Corrected authentication mechanism and corrected google web analytics -m feat(projects): Added ability to have failstate on tasks to easily track tasks that can also fail -m feat(emails): Email features now fully integrated into app along with refresh handling -m fix(forms): Forms performance enhanced greatly -m fix(types): Added additional types to support etended functionality -m fix(sales): Corrected layouts for sales dashboard view (376277d8)
* storybook (cf3edcb7)

#### 1.0.57 (2024-03-06)

##### New Features

* **users:**  Added new user hierarchy managemnet components (23813e36)
* **AI:**  Added AI testing components (68a45d61)
*  Added feed widget (e505299f)

##### Bug Fixes

* **android:**  Project running on android (91c00097)
* **web:**  Major version changes to web app (ebce9a19)
* **visual:**  Major updates, more work done on users screen (b14dad66)
* **users:**  Reverted back (7e88e7b3)
*  Added new form types and fixed some layouts (50a93d06)
*  Implemented fixes for web app (dad1746c)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver (b16bdd45)
* **store:**  Add payment facility (706653c0)

#### 1.0.56 (2024-02-07)

##### New Features

*  Added feed widget (e505299f)

##### Bug Fixes

*  Implemented fixes for web app (dad1746c)

##### Other Changes

* //github.com/smartsaas/smartsaas-resolver (b16bdd45)
* **store:**  Add payment facility (706653c0)

#### 1.0.54 (2023-11-27)

##### Bug Fixes

*  Corrected responsive design and scaling on web [Implemented fix for returning back to main menu item after going into sub-pages #26, Added dynamic release notes and journal on both smartphone and web app #25] (fa8beaf9)