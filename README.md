## Headerless.org

The Headerless Organisation committed itself to promote a streamlined license and copyright process in FOSS projects.

### Why Headerless

The **F**ree and **O**pen **S**ource **S**oftware (FOSS) movement has created a prosperous and almost utopic ecosystem of sharing and collaborating. While the burden of tooling and services around creating, or contributing to FOSS projects has decreased dramatically over the last years, other topics such as licensing are complex to understand and represented itself as intransparent especially for beginners wanting to join the FOSS community. While permissive licenses such as the [MIT](https://opensource.org/licenses/MIT) and [Apache-2.0](https://opensource.org/licenses/Apache-2.0) are easy to understand and comply with, capturing the license situation of a project with mixed licenses on file level is overwhelming and discouraging.

**Headerless.org** therefore promotes to use **no license or copyright headers** in software project and use the centralized approaches to proudly state your FOSS license of choice. In case of a mixed license project, follow the **[12Factor principles](https://12factor.net/dependencies)**  and split your project up into isolated dependencies, each with its individual license.

## 6 Reasons to go Headerless

- **Reduce License Complexity:** People looking at your source code or planning to use your project for further work will have a hard time to go through all your source-files and looking at all the license headers, just to get an overview of the license situation.
- **Reduce Maintenance:** Having to maintain license and copyright headers in all your source files is a maintenance intensive tasks. Having to update the copyright year and adding new copyright for new maintainer not only takes time, but also creates a lot of noise in your commit history.
- **Prevent Redundancy:** Most FOSS projects rely on a single license for the whole project. Mentioning the license in every file again is as redundant as adding the copyright year in every file, while your commit history clearly state the author and date of which your intellectual property has been created.
- **Simplify License Compliance:** While almost all programming eco-systems come with easy ways to state your projects license and have ways to get a list of all licenses used by your projects dependencies, doing the same for license headers with various formats is difficult and known to false-positives.
- **Facilitate Contributions:** When contributing to an FOSS project, there can be uncertainties regarding license and copyright practices. Does a contributer have to add a copyright when he just wants to fix a typo? Should copyrights be removed when rewriting substantial parts of the code? Removing such uncertainties and making the process easy to understand will greatly benefit the willingness to contribute.
- **Empower Sharing Culture:** While license and copyright headers can easily be removed by copycats, permissive licenses explicitly state that copying parts of your source code is allowed, which boost the sharing and re-use culture.

### Join the Movement

Making your project **Headerless.org** compliant is easy and painless:

1. **Omit any copyright and license headers form all source files in your project.**
1. **Follow the eco-system dependant (e.g. `package.json` for NPM) and independent (e.g. `LICENSE` file) best-practises to display your license choice.**

If you want to promote that your project is compliant to **Headerless.org** or simply want to support the movement, add the **Headerless.org** badge to your projects:

> [![Headerless.org](https://img.shields.io/badge/HEADER-LESS-brightgreen.svg)](http://headerless.org)

``` text
[![Headerless.org](https://img.shields.io/badge/HEADER-LESS-brightgreen.svg)](http://headerless.org)
```
