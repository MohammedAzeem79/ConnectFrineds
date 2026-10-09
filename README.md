# ConnecFriend (CS 301 – Assignment 1)

Open `index.html` in a browser. Everything runs client-side (no server calls); state is kept in localStorage.
Bootstrap 5.3 and Bootstrap Icons are bundled in `vendor/` so the app works offline (only the Google font needs internet; a system font is used otherwise).

Demo logins (password = username + 123): ali, sana, hamza, mehwish, bilal, zara, usman, hira.
- Log in as **ali**, try inviting **zara**: she has ignored Ali, so the request is blocked.
- **usman** has a pending request to Ali (People & requests > Requests).
- "Reset demo data" on the login page restores the seed data.

Pages: index.html (login), home.html (feed, sharing, like/dislike), profile.html (profile, friends, ratings),
people.html (invitations, ignore list), messages.html (private messaging with any member).
