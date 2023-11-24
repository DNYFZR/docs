<h1 align="center"><b> 📝 DevOpsHub </b></h1>

<br>

<h4 align="center"><b> ♻ CI / CD  </b></h4>

 **Script** | **Notes**
--|--
[Azure DevOps CI Pipeline](library/CICD/Azure_DevOps_Pipeline.yml) | CI test pipeline for Python projects
[GitHub CI Pipeline](library/CICD/GitHub_CI_Pipeline.yml) | CI test pipeline for Python projects
[GitHub CD Pipeline](library/CICD/GitHub_Build_Pipeline.yml) | Python source code package build pipeline
[GitHub Release Pipeline](library/CICD/GitHub_Release_Pipeline.yml) | Create a release within the GitHub repo

<br>

<h4 align="center"><b> 🐳 Docker  </b></h4>

 **Script** | **Notes**
--|--
[GitHub Docker Build](library/Docker/GitHub_Docker_Build_Pipeline.yml) | Push Docker image to GitHub Packages

<br>

<h4 align="center"><b> 🐧 Linux  </b></h4>

 **Script** | **Notes**
--|--
[Move file to staging dir](library/Linux/raw.yaml) | Move a file to the staging directory, once it arrives in raw
[Transform stage data](library/Linux/stage.yaml) | After raw completes, run python transform pipeline and post output in production dir

---
