## Contact form React Component with PHP mail api.

[![status](https://travis-ci.org/malithmcr/react-php-contact-form.svg?branch=master)](https://travis-ci.org/malithmcr/react-php-contact-form.svg?branch=master)

[![version](https://img.shields.io/badge/version-1.0.1-yellow.svg)](https://semver.org)

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

This is the repo for tutorial in my blog post [Create Contact form with react and php](https://blog.bitsrc.io/how-to-build-a-contact-form-with-react-js-and-php-d5977c17fec0).

## Usage of complete project.

Please clone this repo and in the project root directory, Please run:

### `npm install`

please go to the root fo the project and run npm install to install all the nessery npm modules.

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Build this project for production.


## Using only the component
If you want to use only the react component without using php api.
Please download 'src/components/Form/' folder.

You can use the form component like this  `<Form config={config} />`


## Run PHP API with docker
First you need docker installed in you machine. Once you have docker installed please 
navigate to root folder from your terminal and run:

`docker-compose up -d`

Api will run in localhost:8080


#### props

`config - object`

Example of config prop:

<div align="center">
    <a href="https://www.paypal.me/craftcode"><img alt="Header" src="/config-obj.png?raw=true" width="70%"></a>
</div>

Watch the Video: 
<div align="center">
    <a href="https://www.youtube.com/watch?v=_f16vyORzJ8"><img alt="Header" src="https://img.youtube.com/vi/_f16vyORzJ8/0.jpg" width="70%"></a>
</div>


#### .env

Make sure change api url in .env file

    $ REACT_APP_API = http://localhost/react-contact-form/api/contact/index.php

Change this : http://localhost/react-contact-form/api/contact/index.php to whatever you want.

## PHP Settings

Please go to ./api/config.php

and change adminEmail to your email. You will get email to this.
     $adminEmail =  "hey@malith.dev"; 


<div align="center">
    <a href="https://www.paypal.me/craftcode"><img alt="Header" src="/screenshot.png?raw=true" width="80%"></a>
</div>


## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://craftcode.design/"><img src="https://avatars3.githubusercontent.com/u/4549859?v=4" width="100px;" alt="Malith Priyashan"/><br /><sub><b>Malith Priyashan</b></sub></a><br /><a href="#infra-malithmcr" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/malithmcr/react-php-contact-form/commits?author=malithmcr" title="Tests">⚠️</a> <a href="https://github.com/malithmcr/react-php-contact-form/commits?author=malithmcr" title="Code">💻</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


<div align="center">
    <a href="https://www.paypal.me/craftcode"><img alt="Header" src="https://cdn-images-1.medium.com/max/806/1*G95uyokAH4JC5Ppvx4LmoQ.png" width="20%"></a>
</div>


I wrote a full article about this here: https://blog.bitsrc.io/how-to-build-a-contact-form-with-react-js-and-php-d5977c17fec0
