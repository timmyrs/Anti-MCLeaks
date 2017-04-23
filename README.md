# Anti-MCLeaks

A BungeeCord Plugin preventing Accounts that might not be owned by the player to join your server.

## Installation

1. Download the latest jar from the [releases section](https://github.com/timmyrs/Anti-MCLeaks/releases)
2. Put the jar into the `modules` directory of your bungeecord server
3. Restart your BungeeCord instance

## Commands and Permissions

There is only one command:

### GAML (Global Anti MC Leaks)

- Permission: `antimcleaks.command.gaml`

- Usage:

  - `/gaml` tells you whether Anti-MCLeaks is enabled or disabled
  - `/gaml enable` enables Anti-MCLeaks
  - `/gaml disable` disables Anti-MCLeaks
  - `/gaml <name>` tells you whether the account with the given `<name>` is an MCLeaks-Account
  - `/gaml <uuid>` tells you whether the account with the given `<uuid>` is an MCLeaks-Account

## Credits

Credits to [TheMrGong](https://github.com/TheMrGong/MCLeaksApiClient) for his API. Without their API, this project would not be possible.
