TODO:
- fix frontend imagery
- general UI improvements

EDIT:
- (BUG -- FIXED) rendering produces an empty tag
- (BUG -- FIXED) adding new addresses doesn't work
- (UX -- FIXED) map does not render immediately on entering page

CREATE:
- (UX -- FIXED) hitting enter does nothing in the address field
- (BUG -- FIXED) possible to add invalid values into address fields
- (BUG? i can't reproduce) previously removed paths sometimes stay rendered on the screen

REGISTER:
- (UI) has scrollbars visible on desktop
- (UX) scrolling the register modal scrolls the landing page as well
- (UX) no indication of successful registration

LOGIN:
- (UI) has scrollbars visible on desktop
- (UX) no indication of login failure
- (UX) no warning if user tries to use unregistered email to sign in

EXPLORE:
- { HIGH PRIORITY -- FIXED } strange layout of squares
- { HIGH PRIORITY } pass location data to server

PROFILE:
- (UX) User image is unused
- (UX) no feedback on changing email/password/bio (or failing changes)
