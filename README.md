# Docker Hub Image Conservation
Azure DevOps pipeline to regularly pull all images from a Docker Hub account

## Overview
Docker Hub's retention policy will delete any image tag not pushed/pulled for six months.

This Azure pipeline will pull all images from a Docker Hub account on a schedule to avoid image deletion.

## Usage
Update `ORG` variable in bash script step and amend cron schedule as necessary.

*NOTE:* Azure DevOps scheduled pipelines do not support pipeline variables.
