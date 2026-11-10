# TextRealm

A text-based game that runs as a local server.

## Running

Run `textrealm.com`. It is a single portable executable and picks up automatically whether you are on **Windows** or **Linux**.

```sh
# Linux
chmod +x textrealm.com
./textrealm.com

# Windows
textrealm.com
```

This spawns a game server on **port 9999** of localhost.

## Playing

Connect to the server with netcat:

```sh
nc localhost 9999
```

Everything you play or interact with happens over that connection.

## Crashes

If you crash the game, don't worry. The server automatically restarts the game process under a new PID, so you can just reconnect and keep going.
