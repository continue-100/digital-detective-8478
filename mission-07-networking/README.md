# Mission 7: Networking

## Objective
Understand how computers communicate through networks.

## Concepts Learned
- IP address identifies a device on a network.
- DNS translates domain names into IP addresses.
- HTTP and HTTPS are protocols used to access websites.
- Networks allow devices to exchange data.

## Work Completed
Practiced networking commands and explored how devices connect to websites.

## Commands Used
- ping
- nslookup
- curl

## Understanding
When accessing a website, DNS finds its IP address and the browser communicates with its server using HTTP or HTTPS.

## Evidence
Tested networking commands in Terminal.

## Tools Used
Terminal and macOS networking utilities.

## Network concepts

| Concept | Meaning | Example |
|---|---|---|
| LAN | Network covering a small area | Home network |
| MAN | Network spanning a city or large campus | City network |
| WAN | Network spanning a large geographic area | Internet |
| DNS | Resolves names to addresses | Looking up example.com |
| Router | Forwards traffic between networks | Home router |
| Protocol | Rules for communication | HTTPS |
| Packet switching | Sends data in individually routed packets | Internet traffic |
| Client-server | A client requests a service from a server | Browser and web server |

A connectivity test such as `ping` checks whether a target responds, although a blocked ping does not prove the site is down. `nslookup` displays DNS answers, such as addresses for a domain. DNS helps a browser find an address for a website name. Record your own privacy-safe results for a public example domain: **[observation needed]**.

## Opening a website

1. The browser (client) reads the website address.
2. DNS resolves its domain name to an IP address, unless a usable answer is cached.
3. The client sends traffic through the local network and router towards the server.
4. The client establishes a connection, using TLS for HTTPS.
5. The browser sends a request using the HTTP protocol.
6. The server responds with content and the browser displays it.

Mission commit: `[original history]`. Record your own difficulties and resolutions and verify the latest push.
