# Login Module – Test Scenarios

## Functional
SC-LOGIN-F-01 Verify user can login with valid credentials
SC-LOGIN-F-02 Verify user redirected to dashboard after login
SC-LOGIN-F-03 Verify session created after successful login
SC-LOGIN-F-04 Verify remember me functionality
SC-LOGIN-F-05 Verify logout terminates session
SC-LOGIN-F-06 Verify user role redirects correctly (if multiple roles)
SC-LOGIN-F-07 Verify login works across supported browsers
SC-LOGIN-F-08 Verify login works after password reset
SC-LOGIN-F-09 Verify login works with case-sensitive username (if required)
SC-LOGIN-F-10 Verify system logs login activity

## Negative
SC-LOGIN-N-01 Verify login fails with incorrect password
SC-LOGIN-N-02 Verify login fails with incorrect username
SC-LOGIN-N-03 Verify login fails with empty username
SC-LOGIN-N-04 Verify login fails with empty password
SC-LOGIN-N-05 Verify login fails when account is locked
SC-LOGIN-N-06 Verify login fails when account is inactive
SC-LOGIN-N-07 Verify SQL injection attempt is blocked
SC-LOGIN-N-08 Verify XSS script injection attempt is blocked
SC-LOGIN-N-09 Verify brute-force attempt triggers lockout
SC-LOGIN-N-10 Verify session invalid after manual token manipulation

## Boundary
SC-LOGIN-B-01 Verify username minimum length
SC-LOGIN-B-02 Verify username maximum length
SC-LOGIN-B-03 Verify password minimum length
SC-LOGIN-B-04 Verify password maximum length
SC-LOGIN-B-05 Verify login with special characters in username
SC-LOGIN-B-06 Verify login with maximum allowed failed attempts
SC-LOGIN-B-07 Verify session timeout boundary
SC-LOGIN-B-08 Verify password exactly at minimum required length
SC-LOGIN-B-09 Verify password exactly at maximum allowed length
SC-LOGIN-B-10 Verify login with leading/trailing spaces

## UI/UX
SC-LOGIN-UI-01 Verify login page layout alignment (desktop)
SC-LOGIN-UI-02 Verify login page layout alignment (mobile)
SC-LOGIN-UI-03 Verify password field masks characters
SC-LOGIN-UI-04 Verify show/hide password toggle works
SC-LOGIN-UI-05 Verify error message displays clearly
SC-LOGIN-UI-06 Verify error message disappears after correction
SC-LOGIN-UI-07 Verify login button disabled when fields empty
SC-LOGIN-UI-08 Verify loading indicator after clicking login
SC-LOGIN-UI-09 Verify tab navigation between input fields
SC-LOGIN-UI-10 Verify accessibility labels for screen readers
