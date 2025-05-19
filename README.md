# SkyOffice

![License](https://img.shields.io/badge/license-MIT-blue) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg)

<img alt="Logo" align="right" src="https://user-images.githubusercontent.com/11501902/139942585-a6b044ce-3695-460a-91bd-dd9f1d4611c8.png" width="20%" />

SkyOffice is an immersive virtual office platform that fosters seamless collaboration through real-time interactions. It won the [2021 Monte Jade Innovation Competition](https://www.montejadese.org/innovation-competition) for its innovative approach to remote work.

- **Try it out**: [SkyOffice](https://sky-office.co/)
- **Our vision**: [Concept Video](https://www.youtube.com/watch?v=BpDqGTPh8pc)
- **Stay updated**: Follow our [Twitter](https://twitter.com/SkyOfficeApp)
- **Support us**: Consider [buy me a coffee](https://buymeacoffee.com/lakhanpxlao)

> **Note**: SkyOffice is compatible with all PC browsers. Mobile browsers are currently not supported.

## Project Details

SkyOffice leverages cutting-edge technologies to create a virtual office environment where users can interact as avatars, collaborate in multifunctional rooms, and communicate seamlessly. Key features include proximity-based audio chats, real-time text messaging, screen sharing, and embedded whiteboards, making it an ideal solution for remote teams.

### Built With

- **[Phaser3](https://github.com/photonstorm/phaser)**: Game engine for interactive 2D graphics
- **[Colyseus](https://github.com/colyseus/colyseus)**: WebSocket-based server framework for real-time multiplayer
- **[React/Redux](https://github.com/facebook/react)**: Front-end framework for dynamic UI
- **[PeerJS](https://github.com/peers/peerjs)**: WebRTC for video and screen sharing
- **[TypeScript](https://github.com/microsoft/TypeScript)** & **[ES6](https://github.com/eslint/eslint)**: For robust client and server-side code

## My Role as a Freelance Contributor

As a freelance contributor to SkyOffice, I focused on stabilizing avatar data to ensure smooth and consistent avatar rendering and movement within the virtual office environment. My responsibilities included:

- **Data Optimization**: Enhanced the handling of avatar state data to improve performance and reduce latency during real-time interactions.
- **Server Synchronization**: Improved synchronization between client-side avatars and the Colyseus WebSocket server, ensuring accurate positioning and state updates.
- **User Experience**: Refined avatar movement mechanics to provide a seamless and immersive experience for users navigating the virtual office.

My work contributed to the platform's reliability and enhanced the collaborative experience for remote teams. Connect with me on [GitHub](https://github.com/Arjunlakhanpall) for more about my projects or freelance inquiries.


### Features


- **[Proximity Chat](#proximity-chat)**: Distance-based audio interaction
- **[Flexible Screen Sharing](#flexible-screen-sharing)**: Instant screen sharing capabilities
- **[Multifunctional Rooms](#multifunctional-rooms)**: Versatile spaces for collaboration
- **[Text Message Chat](#text-message-chat)**: Real-time chat with dialog bubbles
- **[Custom/Private Rooms](#customprivate-rooms)**: Personalized and secure rooms
- **[Embedded Whiteboards](#embedded-whiteboards)**: Integrated [WBO](https://github.com/lovasoa/whitebophir) whiteboards via iframe

#### Proximity Chat

![Proximity Chat](https://user-images.githubusercontent.com/11501902/139960852-cf0e0883-8fbe-459d-bb11-3707d0ae1360.png)

#### Multifunctional Rooms

![Multifunctional Rooms](https://user-images.githubusercontent.com/11501902/139961091-1801bd4d-fbd6-4400-8503-85ece744e979.png)

#### Flexible Screen Sharing

![Screen Sharing](https://user-images.githubusercontent.com/11501902/139961155-44a85cd9-ac25-4563-9d82-6537ed7435f6.png)

#### Text Message Chat

![Text Chat](https://user-images.githubusercontent.com/11501902/145925423-3b5b9026-d3b9-429d-920b-98b0bcd6300a.png)

#### Embedded Whiteboards

![Whiteboards](https://user-images.githubusercontent.com/11501902/147785323-19dbf0e6-056d-44c5-8efe-e969297bbe52.png)

#### Custom/Private Rooms

![Custom Rooms](https://user-images.githubusercontent.com/11501902/147784118-15ef50bf-0f67-4704-89d7-81b2fa7f8ceb.png)


## Controls

- **Move**: `W, A, S, D` or arrow keys (video chat activates when near another user)
- **Sit**: `E`
- **Screen Share**: `R` (use computer)
- **Open Chat**: `Enter`
- **Close Chat**: `ESC`

## Prerequisites

- [Node.js](https://nodejs.org/en/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (included with Node.js)
- [Yarn](https://yarnpkg.com/) (optional, for dependency management)

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kevinshen56714/SkyOffice.git
   ```
   To use a custom folder name:
   ```bash
   git clone https://github.com/kevinshen56714/SkyOffice.git my-folder-name
   ```

2. **Start the server**:
   ```bash
   cd SkyOffice
   yarn && yarn start
   ```

3. **Start the client**:
   ```bash
   cd SkyOffice/client
   yarn && yarn dev
   ```

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

If you're using SkyOffice for your virtual office or incorporating our code into other projects, please consider supporting me at [buy me a coffee](https://buymeacoffee.com/lakhanpxlao). Thank you!
