
# Certificate Generator Front End

[![opensource](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/JbossOutreach/certificate-generator-front) 
![license](https://img.shields.io/apm/l/vim-mode.svg?style=popout) [![Build Status](https://travis-ci.org/JBossOutreach/certificate-generator-front.svg?branch=master)](https://travis-ci.org/JBossOutreach/certificate-generator-front) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/4350ebc02efb4442ba256e66d2e4d66e)](https://www.codacy.com/app/JbossOutreach/certificate-generator-front?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JbossOutreach/certificate-generator-front&amp;utm_campaign=Badge_Grade) ![angular](https://img.shields.io/badge/Angular-6-%23f74242.svg) ![node](https://img.shields.io/badge/Node.js-8-blue.svg) ![typescript](https://img.shields.io/badge/Typescript-3.1.1-%2300bfff.svg) [![contributors](https://img.shields.io/github/contributors/JBossOutreach/certificate-generator-front.svg)](https://github.com/JBossOutreach/certificate-generator-front/graphs/contributors/) [![issues](https://img.shields.io/github/issues/JBossOutreach/certificate-generator-front.svg)](https://github.com/JBossOutreach/certificate-generator-front/issues/) [![pull-requests](https://img.shields.io/github/issues-pr/JBossOutreach/certificate-generator-front.svg)](https://github.com/JBossOutreach/certificate-generator-front/pulls) [![Gitter](https://img.shields.io/gitter/room/JBossOutreach/certificate-generator.svg)](https://gitter.im/JBossOutreach/certificate-generator) [![twitter](https://img.shields.io/twitter/follow/jbossorg.svg?label=Follow&style=social)](https://twitter.com/jbossorg) 
 [![forks](https://img.shields.io/github/forks/JBossOutreach/certificate-generator-front.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/JBossOutreach/certificate-generator-front/network/) [![stars](https://img.shields.io/github/stars/JBossOutreach/certificate-generator-front.svg?style=social&label=Star&maxAge=2592000)](https://github.com/JBossOutreach/certificate-generator-front/stargazers/) [![watchers](https://img.shields.io/github/watchers/JBossOutreach/certificate-generator-front.svg?style=social&label=Watch&maxAge=2592000)](https://github.com/JBossOutreach/certificate-generator-front/watchers/)

Certificate Generator aims to automatically generate certificates based on the data provided using input files like CSV and Excel.

## Target Audience
* _**Certificate Issuing Organizations:**_ The Certificate issuing organization will first have to register themselves for authorization. They can generate multiple certificates simply by selecting the template and giving the candidates details through files like csv and excel.

* _**Candidates Receiving the Certificates:**_  The Candidate's dashboard will contain the URLs of all the certificates they have received. This will help them in maintaining all the certificates even if they have lost them locally.

## Development Stack
* HTML
* CSS
* Angular 6 for Front-End

## Work Flow for Developers
* _**For Certificate Issuers:**_
    1. Authenticate the Organization.
    2. The Organization dashboard will display the list of all the certificates generated by that Organization.
    3. Dashboard will allow the user to generate Certificates, single or in bulk.
    4. Based on the selection, we'll proceed to the template selection page.
    5. We'll have a form for single certificate generation and for bulk certificates, we'll allow the Organization to upload a csv or excel file.
    6. We'll allow the user to preview the certificates before the final generation.
    7. After generating the certificates, an email will be sent to all the candidates.

* _**For Candidates:**_
    1. The Dashboard will contain thumbnails of all the certificates received by the student.
    2. There will be an option to view a particular certificate.
    3. The candidate will also be allowed to share the certificate.




### Development Steps

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

#### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

#### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

#### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

#### Application Login Page

![Login](https://raw.githubusercontent.com/JBossOutreach/certificate-generator-front/master/src/assets/wire_login.jpg)

#### Application Sign Up Page

![Signup](https://raw.githubusercontent.com/JBossOutreach/certificate-generator-front/master/src/assets/wire_signup.jpg)

#### Issuer Dashboard
 ![Issuer](https://raw.githubusercontent.com/JBossOutreach/certificate-generator-front/master/src/assets/dash_ment.jpg)

#### Students Dashboard

![Students Dashboard](https://user-images.githubusercontent.com/37747169/49171905-08cb9a00-f359-11e8-8009-0ee8802a5a4b.png)

### Steps to Contribute

   1. Fork the repo  [![fork](https://img.shields.io/github/forks/JBossOutreach/certificate-generator-front.svg?label=Fork&style=social)](https://github.com/JBossOutreach/certificate-generator-front/fork)
   2. Clone the forked repo ` https://github.com/YOUR_USERNAME/certificate-generator-front.git`
   3. Commit changes on your fork.
   4. Create a Pull Request. 
   5. Make sure to follow the contributing guidelines.
 
 You may also create an issue to report any bugs or implementation of a new feature.
  
#### Help

If you need any help anywhere in the process, you can always ask a question on our [Gitter Chat](https://gitter.im/jboss-outreach/gci).
