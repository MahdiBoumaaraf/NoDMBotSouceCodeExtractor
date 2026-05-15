\# NoDMBot Source Viewer



This repository does not contain NoDMBot source code directly.



It provides a GitHub Actions workflow that extracts the reviewable source files from the official Docker image.



The goal is transparency: users can verify the source files extracted from the Docker image without installing Docker Desktop locally.



\## How to use



1\. Fork this repository.

2\. Add these repository secrets:



\- `DOCKERHUB\_USERNAME`

\- `DOCKERHUB\_TOKEN`


ask [Mahdi Boumaaraf](https://t.me/XYF_R) for token



3\. Go to Actions.

4\. Run "Extract NoDMBot Source From Docker Image".

5\. Download the artifact named `NoDMBot-source-view`.



\## Default image



```text

mahdibmrf/nodmbot:x.x

