# Gameserver

A gameserver is a DLL (Dynamic Link Library) that recreates Fortnite's dedicated server functionality. It modifies the game's memory to turn a Fortnite client into a server capable of hosting matches.

Creating a gameserver is complex because many server-related functions are stripped or disabled in Fortnite builds. Developers must recreate these missing systems, including networking and listening functionality, to allow players to connect to the server.

# Redirect
A redirect, in OG Fortnite terms, is usually a DLL (Dynamic Link Library) that redirects Fortnite's HTTP requests to an unofficial server, such as your own computer or a project's server.

Redirects are commonly injected through a launcher or by replacing an existing DLL within Fortnite's files. In some cases, redirection can also be achieved using proxies or standalone programs.

# Backend
A backend, in OG Fortnite terms, is essentially an HTTP server that receives incoming requests from the Fortnite client through a redirect.

At their core, custom backends mimic Epic Games' API responses so that Fortnite can function properly outside of Epic's official services. This is necessary because older versions of Fortnite cannot operate correctly on Epic's current infrastructure due to various compatibility checks and unsupported services.

These custom backends make Fortnite believe it is communicating with the official servers by providing the responses the game expects.
