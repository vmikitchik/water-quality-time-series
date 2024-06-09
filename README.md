# water-quality-time-series
### Installation
To get started with this project, follow these steps:
1. Install git
2. Configure git
4. Install R
5. Install R Studio
6. Clone the repository
7. Load dependencies
<br/><br/>
#### Installing Git

**Windows:**
1. Download the Git installer from the [Git for Windows website](https://git-scm.com/download/win).
2. Run the installer and follow the default settings.

**Mac:**
1. Download the Git installer from the [Git for mac website](https://git-scm.com/download/mac).
2. Run the installer and follow the default settings.

**Linux:**
Use the package manager for your distribution. For example:
```sh
# Debian/Ubuntu
sudo apt-get install git

# Fedora
sudo dnf install git

# Arch
sudo pacman -S git
```
<br/><br/>
#### Configuring Git
After installing Git, configure your username and email. Open a terminal and run the following commands:

```sh
# check if git is installed
git --version
# then set your username and email for making contributions
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
<br/><br/>
#### Installing R
**Windows**
1. Go to the CRAN R Project website.
2. Click on the "Download R for Windows" link.
3. Click on "base" and then "Download R x.x.x for Windows" (where x.x.x is the latest version number).
4. Run the downloaded installer and follow the instructions to complete the installation.

**Mac**
1. Go to the CRAN R Project website.
2. Click on the "Download R for macOS" link.
3. Download the .pkg file for the latest version of R.
4. Open the downloaded file and follow the instructions to install R.

**Linux**

Use the package manager for your distribution. For example:
```sh
# Debian/Ubuntu
sudo apt-get update
sudo apt-get install r-base

# Fedora
sudo dnf install R

# Arch
sudo pacman -S r
```
<br/><br/>
#### Installing RStudio
1. Go to the RStudio website.
2. Download the installer for your operating system (Windows, macOS, or Linux).
3. Run the installer and follow the instructions to install RStudio.
<br/><br/>
#### Cloning the Repository
Clone the repository to your local machine using Git:
```sh
git clone https://github.com/vmikitchik/water-quality-time-series.git
cd water-quality-time-series
```
<br/><br/>
#### Setting up the Environment
This project uses renv to manage R package dependencies. Follow these steps to restore the project environment:
1. Open RStudio on your system
2. Set your working directory to the project directory where you cloned the repository.
3. Run the following commands in the R console:
```r
# Install renv if you don't have it already
install.packages("renv")

# Initialize renv and restore the environment
renv::restore()
```
`renv::restore()` will read the `renv.lock` file and install the required packages at the versions specified.
<br/><br/>
4. **Run the R code:**
- Open the main R script or Rmd file in RStudio.
- Execute the script by clicking the "Run" button or pressing `Ctrl + Enter`.
