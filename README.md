Functional Package for IPsec
===============
[![Build](https://github.com/commoncriteria/ipsec/workflows/Build/badge.svg)
![Validate](https://github.com/commoncriteria/ipsec/workflows/Validate/badge.svg)
[![Validation](https://raw.githubusercontent.com/commoncriteria/ipsec/gh-pages/master/validation.svg)](https://github.com/commoncriteria/ipsec/blob/gh-pages/ValidationReport.txt)
[![SanityChecks](https://raw.githubusercontent.com/commoncriteria/ipsec/gh-pages/master/warnings-badge.svg)](https://github.com/commoncriteria/ipsec/blob/gh-pages/SanityChecksOutput.md)
[![SpellCheck](https://raw.githubusercontent.com/commoncriteria/ipsec/gh-pages/master/spell-badge.svg)](https://github.com/commoncriteria/ipsec/blob/gh-pages/SpellCheckReport.txt)
[![QuickBuild](https://github.com/commoncriteria/ipsec/actions/workflows/quick_build.yml/badge.svg)](https://commoncriteria.github.io/ipsec)
[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/ipsec.svg?maxAge=2592000)](https://github.com/commoncriteria/ipsec/issues) 

## Draft Version

* [Functional Package for IPsec](https://commoncriteria.github.io/pp/ipsec/ipsec-release.html) (html)
* [Functional Package for IPsec](https://commoncriteria.github.io/pp/ipsec/ipsec-release.pdf) (pdf)

## Release Version
Currently, there is no release version.

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/QQQQ/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/ipsec.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects. You shouldn't need to modify it.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
