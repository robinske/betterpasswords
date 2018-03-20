# Recommendations for Web Developers

The following is a list of password recommendations inspired by [NIST](https://pages.nist.gov/800-63-3/sp800-63b.html#-5112-memorized-secret-verifiers)

* At least 14 characters
* Accept all ASCII characters, Unicode characters, and the space character
* Assigned passwords (e.g., when a user requests a new PIN) must be 6 characters and randomly generated
* Never allow password "hints" that are accessible to an unauthenticated user
* Don't prompt for specific info as your password (e.g. "first pet")
* Don't allow "insecure" passwords where insecure includes:
    * pwned passwords
    * dictionary words
    * repetitive or sequential characters (e.g. ‘aaaaaa’, ‘1234abcd’)
    * context-specific words, such as the name of the service, the username, the email, etc.
* If a user tries to change their password to something insecure:
    * notify the user if they're trying to use an insecure password
    * tell them why it's insecure
    * make them choose a different password
* Offer a password-strength meter
* Rate limit failed authentication attempts on a single account
* [**DON'T ENFORCE OTHER COMPOSITION RULES (e.g., requiring mixtures of different character types or prohibiting consecutively repeated characters)**](https://www.wsj.com/articles/the-man-who-wrote-those-password-rules-has-a-new-tip-n3v-r-m1-d-1502124118)
* Don't require that passwords be changed arbitrarily or periodically
* Require that passwords be changed if there is evidence of a breach
* Let people paste their password (so they can use password managers)
* Allow people to see what they typed in (instead of just dots)
* Use approved encryption when transferring data over the network
* Salt and hash your passwords before you store them
    * Don't roll your own crypto. Use a library.
    * Don't roll your own crypto. Use a library.
    * Don't roll your own crypto. Use a library.
    * Don't roll your own crypto. Use a library.
    * Don't roll your own crypto. Use a library.
    * Don't roll your own crypto. Use a library.
