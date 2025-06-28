This is the Rho Beta Epsilon National Board website, hosted through GitHub and powered by [Hugo](https://gohugo.io/). 

It's currently using this theme: https://github.com/devcows/hugo-universal-theme?tab=readme-ov-fileme and the example site to test setup.

---
Setting up the environment to edit this site is easiest on Linux. Additional details on setup and steps for Windows/Mac can be found [here](https://gohugo.io/installation/).

<details>
<summary><strong>Linux Installation Instructions</strong></summary>

1. Install *Hugo* via the command line:  
   - Run the following line in shell:  
     ```bash
     sudo snap install hugo
     ```  
   - Check installation was successful:  
     ```bash
     hugo version
     ```  
   - This should display something like:
     ```bash
     hugo v0.147.9
     ```

2. Install *Go* via the command line:  
   - Run the following line in shell:  
     ```bash
     sudo snap install go
     ```

3. Clone the website [repo](https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon):  
   - If you want to clone with HTTPS:  
     ```bash
     git clone https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon.git
     ```  
   - If you want to clone with SSH:  
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
     hugo server
     ```  
   - View this page at [http://localhost:1313/RhoBetaEpsilon/](http://localhost:1313/RhoBetaEpsilon/)

5. Building and deploying:  
   - Publish the site by running:  
     ```bash
     hugo
     ```  
   - Push your changes to GitHub. On the `Actions` tab, once the workflow run shows a green checkmark, the site will be deployed publicly.  
   - View the site: [National Board site](https://rhobetaepsilonnationalboard.github.io/RhoBetaEpsilon/)

</details>

<details>
<summary><strong>Windows Installation Instructions</strong></summary>

1. Download Go from this [page](https://go.dev/doc/install):
    - Open the MSI file you downloaded and follow the prompts to install Go.
    - Verify that you've installed Go:
        - Open the start menu
        - type `cmd` then hit *enter* key
        - In the command prompt window type:
            ```powershell
            go version
            ```
        - Confirm that the installed version of Go is printed

2. (Optional but recommended) Install Sass
    - Follow this [guide](https://gohugo.io/functions/css/sass/#dart-sass)
    - Installing via the prebuilt binaries is recommended

3. Install the extended edition of Hugo:
    - Open Powershell as an administrator
    - Run:
        ```powershell
        winget install Hugo.Hugo.Extended
        ```
4. Clone the website [repo](https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon):  
   - If you want to clone with HTTPS:  
        ```powershell
        git clone https://github.com/RhoBetaEpsilonNationalBoard/RhoBetaEpsilon.git
        ```  
   - If you want to clone with SSH:  
        ```powershell
        git clone git@github.com:RhoBetaEpsilonNationalBoard/RhoBetaEpsilon.git
        ```  
   - Navigate to wherever you cloned the repo:  
        ```bash
        cd RhoBetaEpsilon
        ```
   - Make sure the theme submodules are correctly cloned:
        ```powershell
        git submodule update --init --recursive 
        ```

5. Running *Hugo*:  
   - To start a development server and see draft content, run:  
     ```powershell
     hugo server
     ```  
   - View this page at [http://localhost:1313/RhoBetaEpsilon/](http://localhost:1313/RhoBetaEpsilon/)

6. Building and deploying:  
   - Publish the site by running:  
     ```powershell
     hugo
     ```  
   - Push your changes to GitHub. On the `Actions` tab, once the workflow run shows a green checkmark, the site will be deployed publicly.  
   - View the site: [National Board site](https://rhobetaepsilonnationalboard.github.io/RhoBetaEpsilon/)

</details>