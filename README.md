# Docker Hub Image Conservation
Azure DevOps pipeline to regularly pull all images from a Docker Hub account

## Overview
Docker Hub's retention policy will delete any image tag not pushed/pulled for six months.

This Azure pipeline will pull all images from a Docker Hub account on a schedule to avoid image deletion.
