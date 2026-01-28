![](/src/images/rsgis_swoop_green_right_align.svg)

A repository for GEO 429: Programming with Spatial Data.

## Table of Contents
- [Getting Started: Clone This Repository](#getting-started-clone-this-repository)
  - [Using HTTPS (Easiest)](#using-https-easiest)
  - [Using SSH (Recommended for regular contributors)](#using-ssh-recommended-for-regular-contributors)
  - [After Cloning](#after-cloning)
- [Installation Guide](#installation-guide)
  - [Git Bash (Windows)](#git-bash-windows)
  - [Miniconda](#miniconda)
  - [Git](#git)
- [About GitLab](#about-gitlab)
  - [Key GitLab Concepts](#key-gitlab-concepts)
  - [Common GitLab Workflows](#common-gitlab-workflows)
- [Resources for Programming with Spatial Data](#resources-for-programming-with-spatial-data)
  - [Python Libraries for Geospatial Analysis](#python-libraries-for-geospatial-analysis)
  - [Learning Resources](#learning-resources)
- [Setting Up SSH Authentication for GitLab](#setting-up-ssh-authentication-for-gitlab)
  - [1. Generate an SSH Key](#1-generate-an-ssh-key)
  - [2. Display and Copy Your Public Key](#2-display-and-copy-your-public-key)
  - [3. Add the Key to GitLab](#3-add-the-key-to-gitlab)
  - [4. Switch Your Repository Remote from HTTPS to SSH](#4-switch-your-repository-remote-from-https-to-ssh)
  - [5. Test Your SSH Connection](#5-test-your-ssh-connection)

## Getting Started: Clone This Repository

To get started with this course, you'll first need to clone this repository to your local machine.

### Using HTTPS (Easiest)

```bash
git clone https://gitlab.com/[username]/geo429.git
cd geo429
```

### Using SSH (Recommended for regular contributors)

If you've set up SSH authentication (see [SSH setup instructions](#setting-up-ssh-authentication-for-gitlab) below):

```bash
git clone git@gitlab.com:[username]/geo429.git
cd geo429
```

**Note**: Replace `[username]` with the actual GitLab username or group name where this repository is located.

### After Cloning

Once you've cloned the repository:
1. Navigate into the project directory: `cd geo429`
2. Check the repository status: `git status`
3. View the repository structure: `ls` (or `dir` on Windows CMD)

## Installation Guide

Before starting with this course, you'll need to install the following tools:

### Git Bash (Windows)

Git Bash provides a Unix-style command-line interface on Windows.

1. Download Git for Windows from [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run the installer
3. Use the default settings (recommended) or customize as needed
4. Select "Git Bash Here" option during installation for easy access from any folder

### Miniconda

Miniconda is a minimal installer for conda, a package and environment manager for Python.

1. Download Miniconda from [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
2. Choose the installer for your operating system:
   - Windows: Download the `.exe` installer
   - macOS: Download the `.pkg` or `.sh` installer
   - Linux: Download the `.sh` installer
3. Run the installer and follow the prompts
4. On Windows, choose whether to add Miniconda to your PATH (recommended for Git Bash usage)
5. Verify installation by opening a terminal and running: `conda --version`

### Git

Git is a distributed version control system for tracking changes in source code.

**Note**: If you installed Git Bash on Windows, Git is already included. Otherwise:

1. Download Git from [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Run the installer for your operating system
3. Use default settings or customize as needed
4. Verify installation by running: `git --version`

**Configuration**: After installation, configure Git with your name and email:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## About GitLab

GitLab is a web-based DevOps platform that provides a complete solution for the software development lifecycle. It offers:

- **Version Control**: Git-based source code management with branching, merging, and history tracking
- **Collaboration**: Issue tracking, merge requests, code reviews, and team wikis
- **CI/CD**: Automated testing and deployment pipelines
- **Project Management**: Milestones, labels, boards, and time tracking

### Key GitLab Concepts

- **Repository**: Storage location for your project files and version history
- **Merge Request (MR)**: Propose changes to the codebase, similar to GitHub's Pull Request
- **Issues**: Track bugs, feature requests, and tasks
- **Branches**: Parallel versions of your code for developing features independently
- **Commits**: Snapshots of your project at specific points in time

### Common GitLab Workflows

1. **Clone** the repository to your local machine
2. Create a new **branch** for your feature or fix
3. Make **commits** as you work on changes
4. **Push** your branch to GitLab
5. Create a **merge request** to propose your changes
6. After review, **merge** your changes into the main branch

For more information, see the [GitLab Documentation](https://docs.gitlab.com/).

## Resources for Programming with Spatial Data

### Python Libraries for Geospatial Analysis

**Core Libraries:**
- **[GeoPandas](https://geopandas.org/)**: Extends pandas for spatial data operations
- **[Shapely](https://shapely.readthedocs.io/)**: Geometric object manipulation and analysis
- **[Rasterio](https://rasterio.readthedocs.io/)**: Read and write raster datasets
- **[Fiona](https://fiona.readthedocs.io/)**: Read and write vector data formats
- **[PyProj](https://pyproj4.github.io/pyproj/)**: Cartographic projections and coordinate transformations
- **[GDAL](https://gdal.org/)**: Translator library for raster and vector geospatial data formats

**Visualization:**
- **[Matplotlib](https://matplotlib.org/)**: Static maps and plotting
- **[Contextily](https://contextily.readthedocs.io/)**: Add basemaps to matplotlib plots
- **[Plotly](https://plotly.com/python/)**: Interactive maps and visualizations
- **[Folium](https://python-visualization.github.io/folium/)**: Interactive web maps with Leaflet.js

**Advanced Tools:**
- **[Xarray](https://xarray.dev/)**: N-dimensional labeled arrays for climate and weather data
- **[RasterStats](https://pythonhosted.org/rasterstats/)**: Zonal statistics for geospatial data
- **[MovingPandas](https://movingpandas.org/)**: Trajectory data analysis
- **[EarthPy](https://earthpy.readthedocs.io/)**: Utilities for working with spatial data
- **[PDAL](https://pdal.io/)**: Point Cloud Data Abstraction Library

**Machine Learning:**
- **[Scikit-learn](https://scikit-learn.org/stable/)**: Machine learning library
- **[PyTorch](https://pytorch.org/)**: Machine learning library
- **[TensorFlow](https://www.tensorflow.org/)**: Machine learning library
- **[Keras](https://keras.io/)**: Machine learning library

### Learning Resources

**Documentation & Tutorials:**
- [GeoPython](https://geo-python.github.io/): Python for geographic data analysis course
- [Automating GIS Processes](https://autogis-site.readthedocs.io/): University of Helsinki course
- [Python for Geospatial Analysis](https://geobgu.xyz/py/): Comprehensive geospatial Python guide
- [Earth Data Science](https://www.earthdatascience.org/): Earth Lab educational resources

**Communities & Forums:**
- [GIS Stack Exchange](https://gis.stackexchange.com/): Q&A for GIS professionals
- [r/gis](https://www.reddit.com/r/gis/): Reddit community for GIS discussion
- [OSGeo](https://www.osgeo.org/): Open Source Geospatial Foundation

**Data Sources:**
- [OpenStreetMap](https://www.openstreetmap.org/): Collaborative map of the world
- [USGS Earth Explorer](https://earthexplorer.usgs.gov/): Satellite imagery and elevation data
- [NASA Earthdata](https://www.earthdata.nasa.gov/): NASA's Earth science data
- [Natural Earth](https://www.naturalearthdata.com/): Public domain map datasets

## Setting Up SSH Authentication for GitLab

SSH (Secure Shell) authentication allows you to connect to GitLab without entering your username and password each time. This is the recommended method for secure, convenient access.

### 1. Generate an SSH Key

In WSL (Windows Subsystem for Linux) or your terminal, generate a new SSH key:

```bash
ssh-keygen -t ed25519 -C "youremailhere@msu.edu"
```

Press Enter to accept the default file location (this creates `~/.ssh/id_ed25519` and `~/.ssh/id_ed25519.pub`).

When prompted for a passphrase, you can either:
- Press Enter to skip (no passphrase)
- Or enter a passphrase for additional security

### 2. Display and Copy Your Public Key

Show the contents of your public key:

```bash
cat ~/.ssh/id_ed25519.pub
```

Copy the entire output (it should start with `ssh-ed25519` and end with your email).

### 3. Add the Key to GitLab

1. Go to [GitLab](https://gitlab.msu.edu)
2. Click your avatar in the top-right → **Preferences**
3. In the left sidebar, click **SSH Keys**
4. Paste your public key into the "Key" field
5. Give it a descriptive title (e.g., "WSL Laptop")
6. Click **Add key**

### 4. Switch Your Repository Remote from HTTPS to SSH

In your repository folder, check your current remote URL:

```bash
git remote -v
```

You should see something like:
```
origin  https://gitlab.msu.edu/GROUP/REPO.git (fetch)
origin  https://gitlab.msu.edu/GROUP/REPO.git (push)
```

Convert it to SSH (replace `GROUP/REPO` with your actual namespace and repository name):

```bash
git remote set-url origin git@gitlab.msu.edu:GROUP/REPO.git
```

### 5. Test Your SSH Connection

Verify that SSH is working correctly:

```bash
ssh -T git@gitlab.msu.edu
```

You should see a message like: `Welcome to GitLab, @username!`

Now test pushing:

```bash
git push
```

You should no longer be prompted for your username and password!