<p align="center">
  <img src="./assets/images/banner.svg" width="100%" alt="HylooSec Official GitHub Banner" />
</p>
<p align="center">
  <a href="https://www.hyloosec.online/">
    <img src="https://img.shields.io/badge/Official_Website-hyloosec.online-1fc7b7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="HylooSec Website" />
  </a>
  <a href="https://github.com/hyloosec-official-creator/hyloosec-documentation">
    <img src="https://img.shields.io/badge/Documentation-Official-302554?style=for-the-badge&logo=readthedocs&logoColor=white" alt="HylooSec Documentation" />
  </a>
  <a href="mailto:hyloosec.official@gmail.com">
    <img src="https://img.shields.io/badge/Contact-HylooSec-0f766e?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact HylooSec" />
  </a>
</p>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Segoe+UI&weight=700&size=24&duration=3000&pause=900&color=73FFF3&center=true&vCenter=true&width=900&lines=Privacy-first+real-time+communication;Secure+messaging+without+phone-number+dependency;React+%7C+Spring+Boot+%7C+Node.js+%7C+Socket.IO;Building+the+future+of+private+communication" alt="HylooSec animated introduction" />
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=hyloosec-official-creator&label=Profile%20Views&color=1fc7b7&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/hyloosec-official-creator?label=Followers&style=flat-square&color=1fc7b7" alt="GitHub followers" />
  <img src="https://img.shields.io/badge/Project_Status-Active_Development-1fc7b7?style=flat-square" alt="Project status" />
</p>
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
About HylooSec
HylooSec is a privacy-focused real-time communication platform designed to provide secure, modern and responsive messaging without requiring users to depend on a phone number for account creation.
The platform combines a modern React interface with dedicated backend services, real-time Socket.IO communication, secure authentication, hybrid data storage and cloud-based media delivery.
Our goal is simple:
> Build a fast, private and dependable communication platform where users remain in control of their identity and conversations.
What makes HylooSec different?
Account creation without phone-number dependency
Unique numeric User ID-based identity
Real-time private messaging
End-to-end encrypted communication design
Chat security using a key or encrypted key file
Online and last-seen status
Sending, sent, delivered and seen message states
Multiple media and document sharing
Long-message support with expandable content
Emoji support
Responsive desktop and mobile experience
Dark and light application themes
Independent JSON-powered documentation system
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Technology Stack
Frontend
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,redux,js,html,css,bootstrap,vite" alt="Frontend technologies" />
</p>
Technology	Purpose
React.js	Component-based user interface
Redux Toolkit	Global authentication, chat, sidebar, file and user state
React Router	Client-side navigation
Socket.IO Client	Real-time events and messaging
HTML5 and CSS3	Semantic structure and responsive design
Vite	Frontend development and production builds
Backend and Real-Time Services
<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,nodejs,express" alt="Backend technologies" />
</p>
Technology	Purpose
Java and Spring Boot	Authentication, account services and REST APIs
Node.js and Express.js	Messaging gateway and conversation services
Socket.IO	Real-time messaging, typing, delivery and seen events
RESTful APIs	Account, message, media and conversation operations
Databases and Storage
<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql" alt="Database technologies" />
</p>
Technology	Purpose
MongoDB	Conversations, messages and real-time user state
PostgreSQL	Structured account and service data
Cloudinary	Media and attachment storage
DevOps and Deployment
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,nginx,git,github,vercel,aws,jenkins,kubernetes" alt="DevOps technologies" />
</p>
Technology	Purpose
Docker	Containerized services
Nginx	Reverse proxy, traffic routing and rate limiting
Render and Railway	Backend deployment and failover
Vercel	Frontend hosting
GitHub Actions	Automated workflows
Git and GitHub	Source control and project collaboration
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
System Architecture
<p align="center">
  <img src="./assets/architecture.svg" width="100%" alt="HylooSec system architecture" />
</p>
High-level request flow
```text
User
  │
  ▼
React + Redux Frontend
  │
  ├── Spring Boot Services
  │     ├── Authentication
  │     ├── Account Management
  │     └── Structured REST APIs
  │
  ├── Node.js + Express Gateway
  │     ├── Conversations
  │     ├── Messages
  │     └── Socket.IO Events
  │
  ├── MongoDB
  │     ├── Messages
  │     ├── Conversations
  │     └── User Presence
  │
  ├── PostgreSQL
  │     └── Structured service data
  │
  └── Cloudinary
        └── Images, videos and documents
```
Real-time message lifecycle
```text
Sending
   ↓
Sent
   ↓
Delivered
   ↓
Seen
```
HylooSec synchronizes message state across the sender, recipient, open conversation and conversation sidebar.
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Major Platform Capabilities
Secure Account System
Users create an account using a preferred identity, password, security question and chat-security method. After registration, HylooSec generates a unique User ID that is used during login.
Real-Time Messaging
Socket.IO enables fast two-way communication, typing indicators, online presence, message delivery updates and seen-state synchronization.
Media and File Sharing
Users can select multiple supported files, preview attachments and send text with media. Individual files can be up to the limit supported by the application.
Privacy-Focused User Discovery
Users are discovered through their unique 10-digit HylooSec User ID instead of public phone-number or email-based search.
Dynamic Documentation
HylooSec documentation is maintained separately as public JSON files and rendered dynamically by the frontend.
```text
GitHub Documentation Repository
              ↓
        Public JSON Files
              ↓
      HylooSec React Frontend
              ↓
 Full Manual or In-App Help Popup
```
This allows documentation updates without rebuilding the main application.
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Official Repositories
Repository	Description	Status
HylooSec	Main HylooSec application and platform source	Active
HylooSec Documentation	JSON-powered user manual and public documentation	Active
Profile Repository	Official GitHub profile presentation and automation	Active
<p align="center">
  <a href="https://github.com/hyloosec-official-creator/hyloosec">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hyloosec-official-creator&repo=hyloosec&theme=transparent&title_color=73fff3&text_color=c9d8df&icon_color=29c7b9&border_color=1c554f" alt="HylooSec repository card" />
  </a>
  <a href="https://github.com/hyloosec-official-creator/hyloosec-documentation">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hyloosec-official-creator&repo=hyloosec-documentation&theme=transparent&title_color=73fff3&text_color=c9d8df&icon_color=29c7b9&border_color=1c554f" alt="HylooSec Documentation repository card" />
  </a>
</p>
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
GitHub Activity
<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=hyloosec-official-creator&show_icons=true&hide_border=false&bg_color=05070b&title_color=73fff3&text_color=c9d8df&icon_color=29c7b9&border_color=1c554f" alt="HylooSec GitHub statistics" />
  <img width="49%" src="https://streak-stats.demolab.com?user=hyloosec-official-creator&background=05070B&border=1C554F&stroke=29C7B9&ring=73FFF3&fire=29C7B9&currStreakNum=EAFDFC&sideNums=EAFDFC&currStreakLabel=73FFF3&sideLabels=9FB4BC&dates=72868E" alt="HylooSec contribution streak" />
</p>
<p align="center">
  <img width="52%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hyloosec-official-creator&layout=compact&bg_color=05070b&title_color=73fff3&text_color=c9d8df&border_color=1c554f" alt="Most used languages" />
</p>
Contribution activity
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hyloosec-official-creator/hyloosec-official-creator/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hyloosec-official-creator/hyloosec-official-creator/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/hyloosec-official-creator/hyloosec-official-creator/output/github-contribution-grid-snake.svg" alt="HylooSec contribution snake animation" />
  </picture>
</p>
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Current Development Focus
Complete the official HylooSec Documentation Center
Improve conversation previews and sidebar synchronization
Continue real-time messaging performance optimization
Strengthen authentication and chat-security workflows
Improve media preview and upload experience
Expand responsive desktop and mobile support
Refine dark and light themes
Improve deployment resilience and service failover
Prepare future communication and account-management features
Product Principles
Every HylooSec update is guided by these principles:
Principle	Meaning
Privacy	Collect only what is required and protect user identity
Security	Protect accounts, messages and sensitive application flows
Performance	Deliver fast, responsive and reliable communication
Simplicity	Keep the user experience understandable and focused
Scalability	Design services that can grow with platform usage
Maintainability	Keep code, infrastructure and documentation organized
Transparency	Clearly explain how users interact with the platform
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Documentation Center
The official documentation repository is being organized into:
```text
hyloosec-documentation/
│
├── manifest.json
├── user-manual/
│   ├── index.json
│   ├── create-account.json
│   ├── login.json
│   ├── forgot-password.json
│   ├── main-chat.json
│   ├── find-user.json
│   └── settings.json
│
├── features/
├── about/
├── faq/
├── privacy/
├── terms/
├── troubleshooting/
└── assets/
```
The user manual currently covers:
Creating a HylooSec account
Logging in
Resetting a forgotten password
Using the main chat interface
Sending text, emojis and files
Understanding timestamps and message states
Viewing user details
Finding users by User ID
Switching themes
Logging out securely
<p align="center">
  <a href="https://github.com/hyloosec-official-creator/hyloosec-documentation">
    <img src="https://img.shields.io/badge/Open_Official_Documentation-1fc7b7?style=for-the-badge&logo=github&logoColor=white" alt="Open HylooSec documentation" />
  </a>
</p>
<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="Section divider" />
</p>
Connect With HylooSec
<p align="center">
  <a href="https://www.hyloosec.online/">
    <img src="https://img.shields.io/badge/Website-www.hyloosec.online-1fc7b7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="mailto:hyloosec.official@gmail.com">
    <img src="https://img.shields.io/badge/Email-hyloosec.official@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/hyloosec-official-creator">
    <img src="https://img.shields.io/badge/GitHub-hyloosec--official--creator-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
</p>
<p align="center">
  <strong>HylooSec. Because your conversations belong only to you.</strong>
</p>
<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="HylooSec footer" />
</p>
