# ENGAGE Content Manager
---

## Version 0.2.5

- Fixes duplicates in cache from publishing locally saved assets
- Fixes resource setting bug arising from publishing immediately after saving
- Fixes Save method calls that missed the Close window call

---

## Version 0.2.4

- Adds Create New Asset buttons in Manager views
- Fixes "Remember Me" setting bug which cleared credentials after login when unchecked

---

## Version 0.2.3

- Single Sign On (SSO) authentication protocol enabled
- Fixed: Thumbnails in ENGAGE Groups tab do not appear (ongoing)
- Fixed: Create New IFX menu no longer breaks when loaded without valid prefab selected

---

## Version 0.2.2

- Fixes thumbnail (infinite-)refresh issues
- Fixes UI repaint/layout-change bugs
- Fixes IFX Prefab asset selection window
- Fixes text formatting issues

### Known Issues

- Thumbnails in ENGAGE Groups tab do not appear (ongoing)

---

## Version 0.2.1

- Fixes thumbnail (infinite-)refresh issues
- Fixes UI repaint/layout-change bugs
- Fixes IFX Prefab asset selection window
- Fixes text formatting issues

### Known Issues

- Thumbnails in ENGAGE Groups tab do not appear (ongoing)
- Unity build crash/infinite loop problem

---

## Version 0.2.0

- Adds IFX creation/management functionality
- Various bug fixes

---

## Version 0.1.5

- Improves caching of thumbnails in Unity Editor (addressing update loop bug)
- Adds asset bundle size warnings and awareness
- Improves error handling and messaging for upload errors
- Adds retry options for unsuccessful upload requests
- General UI improvements


### Known Issues

- Deleted location in Manager keep reappearing

---

## Version 0.1.4

- Remember credentials option added
- Unmask password option added
- Improved `Authentication Failed` popup, including "Forgot password" link option and support email
- Fixes thumbnail "spinner" bug
- Locations can no longer be edited or published while another build is already in progress. A pop-up message will inform the user for the reason, and ask them to please wait for the first to complete before trying to start a new build.

### Known Issues

- Unity repeatedly timing out when updating scene: Unity heavy on using bandwidth/CPU, all other programs d/c then Unity times out
- Deleted location in Manager keep reappearing

---

## Version 0.1.3

### Known Issues

- Scene thumbnail not loading in Location Manager (loading spinner)
- Logging in with my credentials showing logged in as "Engage User"
- Able to attempt to rebuild location without selecting a scene
- Unity repeatedly timing out when updating scene: Unity heavy on using bandwidth/CPU, all other programs d/c then Unity times out
- Deleted location in Manager keep reappearing
- Repeated uploading of locations crashed the project
- Null ref after trying to build again while location is already building

---