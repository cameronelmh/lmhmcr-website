# LMH MCR Website

Official website for LMH MCR.  (If the deployment history is looking a bit funny, it's because I'm doing a clean up!)
This repository contains the source code, styles, assets, and configuration for the site. It's maintained by the LMH Secretary. 

Currently, the project is being cleaned up to improve structure, maintainability, and collaboration practices.

## About

This repository hosts the LMH MCR website.  
It is intended to be a simple, accessible, and easy-to-maintain site that can be updated by future committees.

Historically, most work was done directly on the `main` branch.  
The current goal is to introduce a clearer structure and a safer branch-based workflow using pull requests.


## Quick Start

1. To get started, clone the repository:
```
git clone https://github.com/cameronelmh/lmhmcr-website.git
cd lmhmcr-website
```
If you don't have write access, please get in touch with the contributors to the repo. If it's an emergency, forking and making a PR is also possible, but ideally avoided.

2. Create a new feature branch before making any changes:
```
git checkout -b feat/your-change-name
```
Work in and push to your feature branch. Please do not commit to main!! Main should be for production-ready code only. 

3. Open a PR on GitHub to merge to main
4. Merge upon approval - please resolve any conflicts before merging!!

## Project Structure
By the end of the clean up, I'm hoping it will look like:

```
/assets        Images, fonts, icons
/styles        CSS files
/scripts       JavaScript files
/public        Static public files
/src           Main site files
```

Will come back to this

## Deployment & License

Will document deployment and license details here once confirmed.

## Contact

For questions or issues, please open a GitHub issue or contact the current maintainer (Kaal Sahele).
