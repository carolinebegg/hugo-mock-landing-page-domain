# hugo-mock-landing-page-domain-name

## CIS 3500 Homework #2

### PART III: Automating the Deployment of a Hugo Website (hugo-mock-landing-page-domain-name)

Summary of PART II Tasks + Additional Practice

1. Import hugo-mock-landing-page-autodeployed repository
2. Adjust baseURL in config.toml file
3. Configure repository settings for privacy and where to publish to
4. Add a GitHub Actions workflow to automate the deployment of the landing page
5. Produce line-by-line explanation from Claude
6. Verified the website's deployment
7. Verified the website's deployement after properly updating a change

Here is a concise blurb based on Claude's line-by-line explanation of the workflow code:

*This GitHub Actions workflow automates the process of building and deploying a Hugo-based website to GitHub Pages. When code is pushed to the main branch, the workflow checks out the repository, installs the specified version of Hugo, builds the static site files (including drafts) with minification, and publishes the generated files to the gh-pages branch. The gh-pages branch is then used by GitHub Pages to host the website, making it accessible at a URL like https://<username>.github.io/<repository-name>. The workflow utilizes Git submodules to include external dependencies and separates the source code from the deployed static files for a clean and organized repository structure.*
