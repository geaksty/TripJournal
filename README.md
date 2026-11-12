# TripJournal

Redirect page for the TripJournal application of the Volvo Cars API
(https://developer.volvocars.com).

After signing in with Volvo ID, `index.html` forwards the authorization code to the TripJournal
installation on the owner's home network (a Raspberry Pi). It only forwards to private network
addresses, stores nothing, and sends nothing to third parties.

Served with GitHub Pages: https://geaksty.github.io/TripJournal/
