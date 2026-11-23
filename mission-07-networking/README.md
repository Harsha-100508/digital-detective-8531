# Mission 7 — How computers communicate
## 1. Mission title
Mission 7 — Computer networks and website communication.

## 2. Task / objective
Explain network concepts, observe public connectivity and DNS lookup, and describe the steps used to open a website.

## 3. Work completed
Prepared network definitions, privacy-safe observations, and a numbered browser/server explanation.

### Network concepts
| Concept | Explanation | Example |
|---|---|---|
| LAN | A network covering a small area such as a home or lab. | Office Ethernet and Wi-Fi |
| MAN | A network covering a city or a large campus area. | A university campus network |
| WAN | A network spanning large geographical areas. | The Internet |
| DNS | Translates a human-readable domain name to network addresses. | `example.com` lookup |
| Router | Connects and forwards traffic between networks. | Home or campus router |
| Protocol | A defined set of communication rules. | HTTP and TCP/IP |
| Packet switching | Divides data into packets that are routed and reassembled. | Web page data over IP |
| Client-server | A client requests a service and a server provides it. | Browser requests a web page |

### Network observations
A connectivity test with `ping` to `example.com` sent two packets and received two, with 0.0% packet loss. This indicates that the host was reachable from this network at test time.

A DNS lookup for `example.com` returned public address records. Exact values may change with DNS and network providers, and personal IP details are not included.

- Connectivity testing checks whether network traffic can reach and return from a host.
- DNS lookup displays records that associate a domain name with network addresses.
- DNS lets a browser use a memorable domain name instead of requiring the user to know the server address.

### What happens when a website opens
1. The browser on the client receives the entered domain name and builds a web request.
2. The browser asks DNS to resolve the domain into an IP address.
3. The operating system selects a network route and sends the request through the local network router.
4. TCP and IP protocols divide and route the communication as packets across the network.
5. The packets reach the appropriate example.com server.
6. The server processes the HTTP request and sends a response containing the page resources.
7. The browser validates the response and assembles the resources for the user to view.

## 4. Commands / tools used
`ping -c 2 example.com` and `dig +short A example.com` were used. No personal address or Wi-Fi name was recorded.

## 5. My understanding
DNS, routing, protocols, packets, clients, and servers work together to translate a website name into a usable response displayed by a browser.

## 6. Difficulties faced
Public DNS address results can change between lookups and network locations.

## 7. How I resolved them
I recorded only that address lookup was successful and did not publish unnecessary personal network details.

## 8. Evidence / files
Privacy-safe command observations are recorded in this README.

## 9. Commit details
Commit message: **Explain networking concepts and website communication**. The work was pushed to GitHub.
