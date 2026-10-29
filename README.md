# INCW_10

In-Class Exercise 10 for CS 4370 Web Programming in PHP: cookies and sessions.

Live: https://codd.cs.gsu.edu/~smurugavvel1/WP/INC/inc10/session-cookies-1.php

## Files

- `session-cookies-1.php` tracks the last visit and visit count with cookies and has the login form. Step 11 adds a `random_number` cookie here.
- `session-cookies-2.php` checks the password (`Test`) and sets `$_SESSION['authorized']`.
- `session-cookies-3.php` is the protected page. It only shows its content if that session value is already set.

## Run locally

```
php -S localhost:8000
```

Then open http://localhost:8000/session-cookies-1.php.

To see the step 7 "headers already sent" warning locally, turn output buffering off:

```
php -d output_buffering=0 -S localhost:8000
```
