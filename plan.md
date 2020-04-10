Game of Buttons:

Frontend:

1. A button which, when pressed, makes the a counter go up by one.
2. The button cannot be pressed again until another player has pressed the button.
3. The counter number is stored in memory on the server.

Backend:

1. An express server which holds a counter number.
2. When it receives a GET request, the counter increments by one.
3. The counter cannot be incremented by the same client twice in a row.

Implementing Socket.io:

1. Translate the most simple implementation of socket.io in counter app by receiving logon and logoff messages.
2. Install socket.io on frontend and backend.
3. Require socket.io on backend and write logon/logoff.
4. Import socket.io on frontend.
