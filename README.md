 
# Real-Time Figma Clone Project

This project was built from scratch with a step-by-step approach, demonstrating how to implement key features of a collaborative design tool like Figma in real time. Throughout the development, I utilized modern web technologies and structured the project to focus on reusability, maintainability, and scalability.

## 📝 Content Overview
- 🤖 Introduction
- ⚙️ Technology Used
- 🔋 Key Features
- 🚀 Getting Started
- 🕸️ Code Snippets
- 🔗 Useful Links
- 🚨 Full Tutorial

## 🚀 Overview
This repository contains the full source code for the Real-Time Figma Clone, designed to showcase essential features like real-time collaboration, interactive drawing tools, and live updates. The project highlights important real-world functionalities such as multi-user interactions, custom comments, and responsive design features.

## 🤖 Introduction
I developed this project as a simplified version of Figma, emphasizing real-time collaboration. The core features include live cursors for each user, in-canvas chat, the ability to comment on designs, and the use of **fabric.js** for drawing and editing shapes and images. The project showcases how these components can be integrated to create a smooth, interactive user experience.

If you encounter any issues or have questions, feel free to join my community on Discord, where members help each other with coding, troubleshooting, and project building.

## ⚙️ Tech Stack
- **Next.js**
- **TypeScript**
- **Liveblocks**
- **Fabric.js**
- **Shadcn**
- **Tailwind CSS**

## 🔋 Main Features
- **Multi-User Collaboration**: Real-time collaboration allows multiple users to interact simultaneously, complete with live cursors, chat, and reactions.
- **Active User List**: Displays all users currently working on the canvas in real time.
- **Commenting System**: Attach comments to specific elements on the canvas, facilitating team communication.
- **Shape and Design Creation**: Users can draw various shapes and upload images to the canvas for enhanced design options.
- **Customization**: Modify the properties of elements on the canvas, providing flexibility in the design process.
- **Freeform Drawing**: Enables creative, freehand drawing directly on the canvas.
- **Undo/Redo Functionality**: Easily reverse or restore previous actions.
- **Keyboard Shortcuts**: Boost efficiency with common keyboard commands for tasks like copy, paste, delete, and more.
- **History Review**: Track every change made on the canvas, allowing users to navigate through the project’s evolution.
- **Canvas Management**: Tools to delete, scale, move, clear, and export the canvas for external use.

This project also integrates advanced architectural concepts, including reusable components and efficient state management with React hooks.

## 🤸 Quick Start Guide
To run the project locally on your machine, follow these instructions:

### Prerequisites:
- **Git**
- **Node.js**
- **npm** (Node Package Manager)

### Cloning the Repository:
Simply clone the repository and follow the instructions in the setup guide. You'll have the project running on your local environment in no time!

**Cloning the Repository**

```bash
git clone https://github.com/AMrSamir-Official/figma.git
cd figma
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
```

Replace the placeholder values with your actual Liveblocks credentials. You can obtain these credentials by signing up on the [Liveblocks website](https://liveblocks.io).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173/](http://localhost:5173/) in your browser to view the project.
 