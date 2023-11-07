# Welcome to Ark 🚀
Ark is a software company creating SaaS products for the construction industry 🏗️. Our aim is to boost productivity for designers through cutting-edge software. Our flagship project, Ark, is a SaaS platform that connects purchasers looking to procure modular buildings with manufacturers. We provide end-to-end tools to facilitate this process, including customization, statutory approvals, and progress monitoring 🏠.

## Repository Structure 📚
Our repositories are divided into Back End and Front End:

### Back End 🔧
Ark's Back End is primarily written in .Net (C#) and consists of numerous microservices aggregated through the ArkGateway. We use Clean Architecture with DDD and leverage the MediatR library. Each back end microservice communicates with its own database, and a messaging system handles inter-service communication.

### Front End 🎨
Ark's Front End is built with JS/TS using React and includes several micro front-end applications. The ArkHost is an Azure Static Web app that dynamically pulls micro front-end components from a CDN.

## Code of Conduct 🤝
We're committed to providing a respectful and positive environment for all our contributors. We work hard to create a great platform, and we appreciate your understanding and cooperation. If you encounter any bugs in our software, please reach out to us at [rich@ark.build](mailto:rich@ark.build)!

## Contribution Guidelines 📝
Currently, contributions are limited to Ark staff, but we appreciate bug reports from the community! For internal contributors, please rebase your branch onto main or develop before submitting a PR to make life easier for the branch owner.

## Contact Information 📞
For technical issues, please contact [rich@ark.build](mailto:rich@ark.build). For business inquiries, reach out to [stuart@ark.build](mailto:stuart@ark.build).

## Additional Resources 🔗
Visit our website at [ark.build](https://ark.build) for more information.

## Acknowledgements 🙏
We'd like to thank the following open-source projects that we rely on for Ark:

* Hot Chocolate
* MediatR
* Fluent Assertions
* Apollo Client
* Zustand
* IFC.js
* Ant Design
* Webpack

If we're using your project but missed mentioning it, please reach out, and we'll gladly add you to the list!

## Licensing Information 📄
Ark is a commercial software. Our terms and conditions and privacy policy can be found on our website.
