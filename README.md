<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/trungvd-savvycom/rightpaw">
    <img src="https://rightpaw.com.au/static/media/rightpaw-breeder-badge.525d900a.svg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Right Paw</h3>

  <p align="center">
    We make finding a dog online simpler, safer and more supportive.
    <br />
    <a href="https://github.com/trungvd-savvycom/rightpaw"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/trungvd-savvycom/rightpaw">View Demo</a>
    ·
    <a href="https://github.com/trungvd-savvycom/rightpaw/issues">Report Bug</a>
    ·
    <a href="https://github.com/trungvd-savvycom/rightpaw/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
RightPaw was started by a team of passionate dog lovers who all had the same 'ruff' experience. We went through the painstaking process of trying to find a puppy online. And it was exhausting! So many websites, no transparency around ethical standards, and no support along the way. And this is a big problem, not just for us humans. Many of the issues dogs face - from health concerns, to behavioural problems, and even ending up in shelters - can be traced back to a difficult start in life. We believe the single biggest difference you can make to a dog's life, and the wider industry, is at the very start. So we're building a better beginning. We're here to help every dog and owner start off on the RightPaw.
<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Docker](https://www.docker.com/)
* [Nestjs](https://nestjs.com/)
* [Graphql](https://graphql.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/trungvd-savvycom/rightpaw.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run APP
   ````bash
   cp app/.env.example app/.env
   cp docker/.env.example docker.env

   cd docker
   docker-compose -f docker-compose.local.yml up rightpaw-api
   docker-compose -f docker-compose.local.yml exec rightpaw-api sh -c "npx prisma generate && npx prisma db push && npx prisma db seed"
   ```
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE -->
## Usage

### Web
http://localhost:3001

### GraphQL playground
http://localhost:3000/graphql

### Unit test
```bash
cd docker
docker-compose -f docker-compose.local.yml exec rightpaw-app sh -c "yarn test"
```

_For more examples, please refer to the [Documentation](https://github.com/trungvd-savvycom/rightpaw)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

Comming soon!

See the [open issues](https://github.com/trungvd-savvycom/rightpaw/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/trungvd-savvycom/rightpaw](https://github.com/trungvd-savvycom/rightpaw)

<p align="right">(<a href="#top">back to top</a>)</p>
