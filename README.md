# [react-threejs-3d-world](https://react-threejs-3d-world.web.app/)

<br />
<img src="https://github.com/sctlcd/react-threejs-3d-world/blob/main/design/react-threejs-3d-world-mockup-presentation.png" alt="react-threejs-3d-world" width="800">
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

Creating a 3D world with React, Three.js, React Three Fiber, React Three Drei and React Three Cannon

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
3. Along the top bar, find the “clone or download” button.
4. Here you have the option to clone by HTTPS or SSH.
5. Once you have chose your desired option, then click the copy icon next to the URL.
6. In the terminal, ensure you are in the correct directory which you want to copy the code into. If not, change the directory.
7. Run 

    ````
      git clone https://github.com/sctlcd/react-threejs-3d-world.git
    ````

8. Press the enter button and your clone will be created.
9. Install all modules listed as dependencies in package.json
    
    ```
      npm i 
    ```

    note: in this template [three](https://www.npmjs.com/package/three) - **a JavaScript 3D library**, [vite](https://vitejs.dev/) - **a built in development server**,

10. Install Parcel server, a development server with live reload capability.

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
