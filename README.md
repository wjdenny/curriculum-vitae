# Curriculum Vitae 

This repository holds the data, scripts, templates, and related media for my curriculum vitae. It uses harp and princexml as the main engines for generating documents derived from the data.

# Environment
Originally developed and compiled on Trisquel GNU/Linux 8.0, Flidas, with the following applications.
* node (v10.14.1)
* harp (v0.29.0)
* princexml

## Set up
If you already have node installed, just clone the repository and run the installation script at the root directory.

```
git clone https://github.com/wjdenny/curriculum-vitae.git
cd curriculum-vitae
npm install
```

### Install node
If you don't have node installed, the easiest option is to use the software manager for your distribution. The following will work for Ubuntu-based systems, or those that use the apt package manager.

```
sudo apt-get install node
```

However, something like NVM (node version manager) can be more useful. There are [some instructions](https://www.liquidweb.com/kb/how-to-install-nvm-node-version-manager-for-node-js-on-ubuntu-12-04-lts/) for various distributions that might help.

# Generating documents
First, run the harp server with:

```
harp server ./
```

You can open a browser and view the CV as an HTML document. Or, generate a PDF with:

```
princexml localhost
```

# Issues
If you want to use a similar system for your CV/resume, you can fork this repository and adjust to your liking.
