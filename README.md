<div align="center">
    <img src="https://github.com/Hypfer/Valetudo/blob/master/assets/logo/valetudo_logo_with_name.svg" width="800" alt="valetudo">
    <p align="center"><h2>Free your vacuum from the cloud</h2></p>
</div>

Valetudo is a cloud replacement for vacuum robots enabling local-only operation. It is not a custom firmware.<br/>
Here's a diagram illustrating the core operation principle:

[<img src="https://github.com/Hypfer/valetudo/raw/master/docs/_pages/general/img/operation_principle.png" height=450>](https://github.com/Hypfer/valetudo/raw/master/docs/_pages/general/img/operation_principle.png)

Because Valetudo is not a custom firmware, it cannot change anything about how the robot operates.<br/>
What it can do however is protect your data and enable you to connect your robot
to your home automation system without having to detour through a vendor cloud, which,
apart from the whole data problematic, might not be reachable due to your internet connection
being down or some servers in the datacenter being on fire.

Not having to leave your local network of course also benefits the latency of commands, status reports etc.

Valetudo aims to be proof that easy to use and reliable smart appliances are possible without any cloud and/or account requirements.
Maybe at some point it might help convince vendors that there is another way of doing things.

By default, Valetudo provides control over your vacuum robot via a **responsive webinterface** that works on all of your devices.
It can be used on phones, tablets as well as your desktop computer.


Furthermore, there's a **REST-interface** documented with **Swagger UI** as well as **MQTT**.
With support for both **Homie** and **Home Assistant Autodiscovery** for MQTT, you should be able to connect Valetudo to
the open-source smarthome software of your choice.

For more information, check out the [newcomer guide](https://valetudo.cloud/pages/general/newcomer-guide.html),
the [getting started guide](https://valetudo.cloud/pages/general/getting-started.html) 
and also the docs in general at [https://valetudo.cloud](https://valetudo.cloud)

There, you will find a list of [supported robots](https://valetudo.cloud/pages/general/supported-robots.html).

## Screenshots

### Phone/Mobile
<img src="https://user-images.githubusercontent.com/974410/211155741-d6430660-a6b2-48ab-8ddc-2217328444de.png" width=360> <img src="https://github.com/user-attachments/assets/eaad6fe0-dd1e-4f56-b6f9-f65954aecac7" width=360>

<img src="https://user-images.githubusercontent.com/974410/211155650-7cac266c-ffeb-432d-8656-5241a5d6f227.png" width=360> <img src="https://user-images.githubusercontent.com/974410/211155656-d43ee25e-1ae6-432f-95ff-1a39d294828d.png" width=360>

### Tablet/Desktop

![image](https://github.com/user-attachments/assets/dc18723f-b15f-4500-907b-bad6d7dd1a4f)

![image](https://user-images.githubusercontent.com/974410/211155836-9199616a-efde-4238-91c4-24158ba67677.png)

![image](https://user-images.githubusercontent.com/974410/211155860-9926b126-d1fe-41b1-8c83-1af21bf8caf2.png)

![image](https://user-images.githubusercontent.com/974410/211155880-ff184776-86fe-4c2f-9556-4d556cfa12f4.png)

## Tech Stack
polonia/Valetudo is built on the following main stack:

- <img width='25' height='25' src='https://img.stackshare.io/service/1143/Handlebars.png' alt='Handlebars.js'/> [Handlebars.js](http://handlebarsjs.com/) – Templating Languages & Extensions
- <img width='25' height='25' src='https://img.stackshare.io/service/1209/javascript.jpeg' alt='JavaScript'/> [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) – Languages
- <img width='25' height='25' src='https://img.stackshare.io/service/989/ruby.png' alt='Ruby'/> [Ruby](https://www.ruby-lang.org) – Languages
- <img width='25' height='25' src='https://img.stackshare.io/service/1612/bynNY5dJ.jpg' alt='TypeScript'/> [TypeScript](http://www.typescriptlang.org) – Languages
- <img width='25' height='25' src='https://img.stackshare.io/service/1014/IoPy1dce_400x400.png' alt='.NET'/> [.NET](http://www.microsoft.com/net/) – Frameworks (Full Stack)
- <img width='25' height='25' src='https://img.stackshare.io/service/1163/hashtag.png' alt='ExpressJS'/> [ExpressJS](http://expressjs.com/) – Microframeworks (Backend)
- <img width='25' height='25' src='https://img.stackshare.io/service/1011/n1JRsFeB_400x400.png' alt='Node.js'/> [Node.js](http://nodejs.org/) – Frameworks (Full Stack)
- <img width='25' height='25' src='https://img.stackshare.io/service/1020/OYIaJ1KK.png' alt='React'/> [React](https://reactjs.org/) – Javascript UI Libraries
- <img width='25' height='25' src='https://img.stackshare.io/service/3350/8261421.png' alt='React Router'/> [React Router](https://github.com/rackt/react-router) – JavaScript Framework Components
- <img width='25' height='25' src='https://img.stackshare.io/service/11559/zustand.png' alt='Zustand'/> [Zustand](https://github.com/react-spring/zustand) – State Management Library
- <img width='25' height='25' src='https://img.stackshare.io/service/3670/mqtticon-large_400x400.png' alt='MQTT'/> [MQTT](http://mqtt.org/) – Message Queue
- <img width='25' height='25' src='https://img.stackshare.io/service/3337/Q4L7Jncy.jpg' alt='ESLint'/> [ESLint](http://eslint.org/) – Code Review
- <img width='25' height='25' src='https://img.stackshare.io/service/11563/actions.png' alt='GitHub Actions'/> [GitHub Actions](https://github.com/features/actions) – Continuous Integration
- <img width='25' height='25' src='https://img.stackshare.io/service/832/mocha.png' alt='Mocha'/> [Mocha](http://mochajs.org/) – Javascript Testing Framework
- <img width='25' height='25' src='https://img.stackshare.io/service/324/default_a24de002cfb2ec1db1c531b1449499b5b0c3a95c.png' alt='Semaphore'/> [Semaphore](https://semaphoreci.com/) – Continuous Integration
- <img width='25' height='25' src='https://img.stackshare.io/no-img-open-source.png' alt='axios'/> [axios](https://github.com/mzabriskie/axios) – Javascript Utilities & Libraries
- <img width='25' height='25' src='https://img.stackshare.io/service/10865/default_5551fb8853689f607a2bc0d5a09355d5a3d52bf0.png' alt='date-fns'/> [date-fns](https://date-fns.org/) – Javascript Utilities & Libraries
- <img width='25' height='25' src='https://img.stackshare.io/service/6883/repo-banner.png' alt='pkg'/> [pkg](https://www.npmjs.com/package/pkg) – Javascript Utilities & Libraries

Full tech stack [here](/techstack.md)


## Further questions?
[Valetudo Telegram group](https://t.me/+k-ukcsX2ZYg5MDky)

## Contributing

Make sure to familiarize yourself with the [./CONTRIBUTING.md](./CONTRIBUTING.md)


## Honourable mentions

Valetudo and its companion applications are developed using JetBrains IDEs such as [WebStorm](https://www.jetbrains.com/webstorm/).
Licenses for those have been provided for free by JetBrains to the project in context of [their open source support program](https://jb.gg/OpenSourceSupport) since multiple years now.

Thanks a lot for that!
