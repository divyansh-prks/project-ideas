Insipiration from this [Video](https://youtu.be/8L5kVBays24?si=7k5mddFfEqh5ptKv)

## Project Ideas
<br>

|  | ♟️ CHESS ♟️ |
| :----: | :---: |
| 01 | Build a multiplayer chess game like https://chess.com |
| 02 | Frontend should allow users to signup, create accounts and create a room |
| 03 | On room creation, they can share the link with their friend who can join the group as well
| 04 | Add move validation to make sure users can only make valid moves
| 05 | Use either canvas or raw HTML blocks for the game. You may also use a game engine like phaser. |
| 06 | You will need to do socket programming since this is a real-time game. |

<br>
<br> 

|  | 🐤 MULTIPLAYER FLAPPY BIRD GAME 🐤 |
| :----: | :---: |
| 01 | Create a multiplayer flappy bird game where users can invite their friends and play against each other like [this project.](https://github.com/ourcade/flappy-bird-hathora)|
| 02 | Use raw canvas for rendering, and write all physics yourself (Basic physics like acc, velocity ...) |
| 03 | You will need to do socket programming since this is a real-time game. Sockets would relay the positions of users to each other. |

<br>
<br>

|  | 🤖 CREATE A UI ON TOP OF CHAT-GPT API 🤖 |
| :----: | :---: |
| 01 | Create a ChatGPT clone using their APIs |
| 02 | Use their APIs on the backend, relay the information to your frontend |
| 03 | Make sure your frontend experience is 10x better than the native chat GPT experience. |
| 04 | Allow users to put in their own Chat GPT API keys and use GPT 4. |

<br><br>

|  | CREATE A LOW LATENCY TRADING SYSTEM IN RUST |
| :----: | :---: |
| 01 | Create a WebSocket server in rust |
| 02 | Send data that looks similar to trading applications (create order, cancel order) |
| 03 | Compress data as much as you can. Read about pbfs |
| 04 | Regionally distribute this trading application and send trades closer to the main server |

<br><br>

|  | 🔗 CREATE A MULTICHAIN AIRDROPPING WEBSITE 🔗 |
 :----: | :---: |
| 01 | Build a website that lets users airdrop various crypto currencies to them on their respective testnets |
| 02 | User should be allowed to select the chain (ETH, SOL, Polygon, ARB) and put in an address where they want the native token sent |
| 03 | User should be able to select the amount they want to  |
| 04 |	Implement a user authentication system to ensure the security of user data and prevent fraud or abuse of the airdropping feature.
| 05 |	Enable users to easily view their airdropped tokens and transaction history for each chain on the website.
| 06 |	Include a feature that allows users to track the progress of their airdropped tokens, such as through email notifications or real-time updates on the website.
| 07 |	Consider implementing a referral program that incentivizes users to share the website with their friends and family.
| 08 |	Ensure that the website is optimized for mobile devices, as many users may prefer to access the website from their smartphones.
| 09 |	Provide clear and concise instructions on how to use the website and participate in the airdrops to minimize confusion and errors.
| 10 |	Consider partnering with other crypto projects to offer exclusive airdrops or promotional offers to users of the website, which could help attract more users and increase engagement.
| 11 |	Make sure to comply with all relevant regulations and laws in the jurisdictions where the website will be accessible, as failure to do so could result in legal and financial consequences.
| 12 |	Regularly update and maintain the website to ensure that it remains secure and functional, and to address any bugs or issues that may arise.

<br><br>

|  | Build a Http Server |
| :----: | :--- |
| **01** | Set up a basic C++ project and include necessary libraries (`sys/socket.h`, `arpa/inet.h`, `unistd.h`, or `boost::asio`). |
| **02** | Create a **TCP server** that binds to a port and listens for incoming connections. |
| **03** | Accept client connections using `accept()` and handle multiple clients (single-threaded or multi-threaded). |
| **04** | Read incoming **HTTP requests** and parse the request line (GET/POST, URL, HTTP version). |
| **05** | Parse **HTTP headers** and handle request bodies (especially for POST requests). |
| **06** | Implement routing logic to handle different paths (`/`, `/about`, `/api/data`). |
| **07** | Send an **HTTP response** with proper headers (`Content-Type`, `Content-Length`, `Connection: keep-alive`). |
| **08** | Serve **static files** (HTML, CSS, JS) by reading them from the disk and sending them as responses. |
| **09** | Implement **error handling** (404 Not Found, 500 Internal Server Error, malformed requests). |
| **10** | Add **support for query parameters** (`/search?q=example`) and parse them correctly. |
| **11** | Handle **POST requests** and process incoming form data or JSON payloads. |
| **12** | Implement **multi-threading** or an event-driven model for handling concurrent requests efficiently. |
| **13** | Optimize server performance using **connection keep-alive** and response caching. |
| **14** | Secure the server by implementing **HTTPS with TLS/SSL** (using OpenSSL). |
| **15** | Log requests, responses, and errors for **monitoring and debugging**. |
| **16** | Test the server using **Postman, curl, or a web browser** to ensure correct functionality. |
| **17** | Package the server code and provide **clear documentation** on how to use and run it. |
