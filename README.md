# <img src=".gitlab/avatar.png" alt="avatar" height="20"/>  Procesy CI/CD dla projektów w grupie pl.rachuna-net

Procesy do ciągłej integracji i dostarczania (CI/CD) dla projektów w grupie pl.rachuna-net

[![](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/badges/release.svg)](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/releases)
[![](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/badges/main/pipeline.svg)](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/commits/main)

---
## Workflows

| process      | description |
|--------------|-------------|
|[.gitlab-ci.yml](.gitlab-ci.yml)| default     |
|[cicd/gitlab-components.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/cicd/gitlab-components.yml?ref_type=heads)| Proces dla 
|[infrastructure/terraform.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/infrastructure/terraform.yml?ref_type=heads)| Proces dla terraform|
|--------------|-------------|
|[cicd/gitlab-ci.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/cicd/gitlab-ci.yml?ref_type=heads)| Proces dla gitlab-ci|
gitlab-components|
|[containers/docker.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/containers/docker.yml?ref_type=heads) | Proces dla budowania kontenerów |
|[infrastructure/ansible-playbook.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/infrastructure/ansible-playbook.yml?ref_type=heads)| Proces deploymentu za pomocą ansible|
|[infrastructure/ansible-roles.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/infrastructure/ansible-roles.yml?ref_type=heads)| Proces wydawniczy dla ansible roles|
|[infrastructure/packer.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/infrastructure/packer.yml?ref_type=heads)| Proces dla packer|
|[mkdocs/pages.yml](https://gitlab.com/pl.rachuna-net/cicd/gitlab-ci/-/blob/main/mkdocs/pages.yml?ref_type=heads)| Proces wydawniczy mkdocs na pages |

---
## Contributions
Jeśli masz pomysły na ulepszenia, zgłoś problemy, rozwidl repozytorium lub utwórz Merge Request. Wszystkie wkłady są mile widziane!
[Contributions](CONTRIBUTING.md)

---
## License
Projekt licencjonowany jest na warunkach [Licencji MIT](LICENSE).

---
# Author Information
### &emsp; Maciej Rachuna
# <img src="https://gitlab.com/pl.rachuna-net/gitlab-profile/-/raw/main/assets/logo/website_logo_transparent_background.png" alt="rachuna-net.pl" height="100"/>