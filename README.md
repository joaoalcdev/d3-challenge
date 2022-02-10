<div align="center">
  <h1>
    <p text-align="">D3 Code Challenge</p> <img alt="D3 Logo" height="80" title="Plant Manager" src="./assets/logo.svg" /> 
  </h1>
</div>

<p align="center">
  <img 
    src="https://img.shields.io/cocoapods/l/m?color=%23000000&label=license&logo=license&logoColor=%23ffffff" 
    alt="License" 
  />
  <img 
    src="https://img.shields.io/badge/Code_Challenge-D3-%23000000"
    alt="D3 Challenge" 
   />
  <img 
    src="https://img.shields.io/badge/Tests-Total%3A%207%20%7C%207%20%E2%9C%85%20%7C%200%20%E2%9D%8C%20%7C-%23000000"
    alt="Tests" 
   />
</p>

## 📷 Demonstration

<div align="center">
  <h1 align="center">

  [Click here](https://youtu.be/xZ-4Mbft59Q) to watch the project demo video.

  <img 
    src="./assets/cover.gif?style=flat"
    alt="Cover Project" 
  />

  </h1>
</div>

## 💻 Project

Application developed to have a basis to predict a possible contagion of covid during the next few days.

## :hammer_and_wrench: Features

- [x] OurWolrdInData API's Covid19.
- [x] Connection to OurWolrdInData Covid19 Database;
- [x] Node.js application console input;
- [x] Node.js application result on console;
- [x] Covid 19 contagion forecast in the world.

## ✨ Technologies

- [x] Javascript
- [x] Node.js
- [x] Yarn
- [x] Jest
- [x] Axios
- [x] Dayjs
- [x] Readline Sync

## 🔨 Architecture and Infrastructure for the Project

- Architecture:
  I would choose serverless as a viable option for this job. I would use a 'Function as a Service' (FaaS) like AWS Lambda. Serverless is a software and application design approach that allows developers to create and run services without having to manage and "configure" the work environment, as serverless as a cloud provider can predict and configure servers for future execution of their applications. , database and cloud storage systems as a function of scale.

- Infrastructure:
  An application's infrastructure is based on performance, user experience, user interface experience, and structuring. Given this, a current application infrastructure would have a graphical interface for a better experience and usability of the system, thus improving the user experience. So for that, the interface would call a serverless function that can serve, Cloud Functions or Lambda Functions with a cache like a Redis, for example, for in-memory data. We can use React.Js or Next.Js and Node.js with libraries to create graphs with the result values ​​entered and executed in the backend by the APIs. Hosting by Vercel is interesting, as the platform creates and configures the serverless environment. I would use centry to capture possible errors that can happen in the application and together with that, we could use Jest to create automated testing services and code verification. 

## 🔖 Layout

You can view the project layout through this [link](https://www.figma.com/file/JSBTu7MnPcRxoIdOE6Xp9u/D3-%7C-Code-Challange?node-id=0%3A1). It is necessary to have an account [Figma](http://figma.com/) to access.

## 💻 Challenge Proposal

![cover](./assets/cover.svg?style=flat)

## ⚙️ Running the project

Use **yarn** or **npm install** to install project dependencies.
Then start the project.

After installing the dependencies, use

```cl
yarn start
```

or

```cl
npm init
```

## 📄 License

This project is under MIT license. See the file [LICENSE](./LICENSE) for more details.

<br />

---

Made with 🤍 by [João Alcântara](https://github.com/joaoalcdev) 👋🏻
