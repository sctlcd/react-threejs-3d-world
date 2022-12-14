# [react-threejs-3d-world](https://react-threejs-3d-world.web.app/)

<br />
<img src="https://github.com/sctlcd/react-threejs-3d-world/blob/main/design/react-threejs-3d-world-preview.png" alt="react-threejs-3d-world" width="800">
<br />

---

# Table of Contents <a name="tableOfContents"></a>

1. [Introduction](#introduction)

2. [Run the project locally](#runLocally)

3. [Deployment](#deployment)
	- [Deployment – Run locally](#deploymentRunLocallydeploymentRunLocally)
	- [Deployment – Live website](#deploymentLiveWebsite)

4. [Credits](#credits)
	- [Media](#media)

---

## Introduction <a name="introduction"></a>

Creating a desktop 3D world with React, Three.js, React Three Fiber, React Three Drei and React Three Cannon

- on click: the box rises
- on context menu event / click right on the box: the box increases its size
- on pointer over: the box becomes blue
- on pointer out: the box becomes red

Back to [top](#tableOfContents)

---
## Run the project locally <a name="#runLocally"></a>

Install [Vite](https://vitejs.dev/), a development server with live reload capability.

  - To install:
    
    ```
      npm create vite@latest
    ```

  - To run (from your local directory):
        
    ```
      npm run dev
    ```

Back to [top](#tableOfContents)

---

## Deployment <a name="#deployment"></a>
### Deployment – Run locally <a name="#deploymentRunLocally"></a>

1. Prerequisite:  
    - Make sure [Node](https://nodejs.org/en/) and [NPM](https://www.npmjs.com/) are installed on your computer. You can download both at nodejs.org (NPM is included in your Node installation).
    - Please see `.nvmrc` file at the root of `react-threejs-3d-world` repo.
    - Using nvm, a Node Version Manager is recommended as it helps you manage and switch between different Node versions with ease. It provides a command-line interface where you can install different versions with a single command, set a default, switch between them, etc.
2. In GitHub click on the repository nammed [react-threejs-3d-world](https://github.com/sctlcd/react-threejs-3d-world)
3. Clone the repository locally. Run

    ````
      git clone https://github.com/sctlcd/react-threejs-3d-world.git
    ````

4. Install all modules listed as dependencies in package.json
    
    ```
      cd react-threejs-3d-world
      npm i 
    ```

    note: in this app 
    - [three](https://www.npmjs.com/package/three) - **a JavaScript 3D library**
    - [vite](https://vitejs.dev/) - **a built in development server**
    - [react](https://reactjs.org/) - **JavaScript library for creating user interfaces**
    - [react-dom](https://www.npmjs.com/package/react-dom) - **package that serves as the entry point to the DOM and server renderers for React**
    - [react-three/fiber](https://www.npmjs.com/package/@react-three/fiber) - **React renderer for threejs**
    - [react-three/drei](https://www.npmjs.com/package/@react-three/drei?activeTab=readme) - **collection of useful helpers and fully functional, ready-made abstractions for @react-three/fiber**
    - [react-three/cannon](https://www.npmjs.com/package/@react-three/cannon) - **React hooks for cannon-es to use incombination with @react-three/fiber**

5. Install [Vite](https://vitejs.dev/), a development server with live reload capability.

    - To install:
      
      ```
        npm create vite@latest
      ```

    - To run (from your local directory):
          
      ```
        npm run dev
      ```

Back to [top](#tableOfContents)

---

### Deployment - Live Website <a name="#deploymentLiveWebsite"></a>

[react-threejs-3d-world](https://github.com/sctlcd/react-threejs-3d-world) live website is currently deployed on [Firebase](https://firebase.google.com/) using the `main` branch on GitHub. Once you have the project setup locally, you can proceed to deploy it remotely.

1. Install Firebase CLI Tools, [firebase-tools](https://www.npmjs.com/package/firebase-tools)

    ```
      npm install -g firebase-tools
    ```

2. Create firebase.json and .firebaserc at the root of your project with the following content:

    `firebase.json`:

    ```
      {
        "hosting": {
          "public": "dist",
          "ignore": [],
          "rewrites": [
            {
              "source": "**",
              "destination": "/index.html"
            }
          ]
        }
      }
    ```

    `.firebaserc`:

    ```
      {
        "projects": {
          "default": "<YOUR_FIREBASE_ID>"
        }
      }
    ```

3. After running `npm run build`, deploy using the command `firebase deploy`.


=> live link: https://react-threejs-3d-world.web.app/

Back to [top](#tableOfContents)

---

## Credits <a name="credits"></a>

### Media <a name="media"></a>

- [favicon.ico](https://www.flaticon.com/free-icon/block_2592226?term=3d&page=1&position=72&page=1&position=72&related_id=2592226&origin=search) - [Flaticon](https://www.flaticon.com/) | copyright [Freepik](https://www.freepik.com)

Back to [top](#tableOfContents)

---
