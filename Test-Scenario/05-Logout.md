# Logout Module – Test Scenarios

## Functional
SC-LOGOUT-F-01 Verify user can logout successfully
SC-LOGOUT-F-02 Verify user redirected to login page after logout
SC-LOGOUT-F-03 Verify session token invalidated after logout
SC-LOGOUT-F-04 Verify user cannot access dashboard after logout
SC-LOGOUT-F-05 Verify cart data persists correctly after re-login
SC-LOGOUT-F-06 Verify logout works from all pages (header menu)
SC-LOGOUT-F-07 Verify logout works across supported browsers
SC-LOGOUT-F-08 Verify logout after session timeout behaves correctly
SC-LOGOUT-F-09 Verify logout from multiple tabs synchronizes correctly
SC-LOGOUT-F-10 Verify login page displayed clean state after logout
  
## Negative
SC-LOGOUT-N-01 Verify system blocks access to protected URL after logout
SC-LOGOUT-N-02 Verify back button does not restore authenticated session
SC-LOGOUT-N-03 Verify manual session token reuse rejected
SC-LOGOUT-N-04 Verify expired session cannot perform logout action
SC-LOGOUT-N-05 Verify logout while performing checkout
SC-LOGOUT-N-06 Verify logout during cart update
SC-LOGOUT-N-07 Verify direct API call after logout rejected
SC-LOGOUT-N-08 Verify multiple rapid logout clicks handled safely
SC-LOGOUT-N-09 Verify logout during network interruption
SC-LOGOUT-N-10 Verify session cookie removed after logout

## Boundary
SC-LOGOUT-B-01 Verify logout at session timeout boundary
SC-LOGOUT-B-02 Verify logout immediately after login
SC-LOGOUT-B-03 Verify logout after long idle period
SC-LOGOUT-B-04 Verify logout with maximum session duration
SC-LOGOUT-B-05 Verify logout when cart has maximum items
SC-LOGOUT-B-06 Verify logout while multiple background requests active
SC-LOGOUT-B-07 Verify logout when user role changes
SC-LOGOUT-B-08 Verify logout during concurrent tab activity
SC-LOGOUT-B-09 Verify logout with minimal session data
SC-LOGOUT-B-10 Verify logout when token near expiry

## UI/UX
SC-LOGOUT-UI-01 Verify logout button visible in header
SC-LOGOUT-UI-02 Verify logout button accessible on mobile
SC-LOGOUT-UI-03 Verify confirmation dialog (if applicable)
SC-LOGOUT-UI-04 Verify logout button disabled during processing
SC-LOGOUT-UI-05 Verify loading indicator during logout
SC-LOGOUT-UI-06 Verify no residual user data displayed after logout
SC-LOGOUT-UI-07 Verify error message displayed if logout fails
SC-LOGOUT-UI-08 Verify proper redirect animation or transition
SC-LOGOUT-UI-09 Verify accessibility (keyboard logout support)
SC-LOGOUT-UI-10 Verify session expired message displayed clearly
