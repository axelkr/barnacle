# Barnacle
This documents the various -barnacle repositories and how they connect.

As a user, you get an application, which provides a Heijunka board. The corresponding changes are stored as events in a backend. Changes by one frontend are forwarded - via the backend - to all connected frontends. You can run the application as a single-page application or install as a application.

# choicest-barnacle
Provides type for ObjectEvent, which are used to transfer individual changes between frontend and backend.

# happy-barnacle
Backend server, which provides a REST API and server-sent events for ObjectEvent. Changes are stored locally in a database.

# prime-barnacle
Frontend component, which connects to the backend and takes care of connectivity issues of the network.

# outstanding-barnacle
Domain model of a Heijunka board. Each change is an ObjectEvent.

# eximious-barnacle
Angular webpage, which stores changes to the Heijunka board as ObjectEvents in the backend.

# sterling-barnacle
Packages the backend and the webpage into a single page application.

# solid-barnacle
Packages the backend and the webpage into a installable application.
