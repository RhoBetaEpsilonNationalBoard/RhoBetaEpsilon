This is the Rho Beta Epsilon National Board website, hosted through GitHub and powered by [Hugo](https://gohugo.io/). It's currently using this thehttps://github.com/devcows/hugo-universal-theme?tab=readme-ov-fileme and the example site to test setup.
---
Setting up the environment to edit this site is easiest on Linux. Additional details on setup and steps for Windows/Mac can be found [here](https://gohugo.io/installation/).
# [Linux](https://gohugo.io/installation/linux/) Setup Guide
1. Install *Hugo* via the command line:
 - Run the following line in shell: 
 ```bash
 sudo snap install hugo
 ```
 - Check installation was successful: 
 ```bash
 hugo version
 ```
 - This should display something like ```hugo v0.147.9```
 2. Install *Go* via the command line:
- Run the following line in shell:
```bash
sudo snap install go
```
3. Clone the website [repo](https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon):
- If you want to clone with https: 
```bash
git clone https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon.git
```
- If you want to clone with ssh:
```bash
git clone git@github.com:RhoBetaEpsilonNationalBoard/RhoBetaEpsilon.git
```
- Navigate to wherever you cloned the repo:
```bash
cd RhoBetaEpsilon
```
4. Running *Hugo*:
- To start a development server and see draft content, run:
```bash
hugo server -D
```
- View this page at [http://localhost:1313/](http://localhost:1313/)
5. Building and deploying:
- Publish the site by running:
```bash
hugo
```
- Push your changes to GitHub. On the `Actions` tab, once the workflow run shows a green checkmark, the site will be deployed publicly. 
- View the site: [National Board site](https://rhobetaepsilonnationalboard.github.io/RhoBetaEpsilon/)
