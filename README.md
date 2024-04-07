# Reusable Workflows repo 

### Included working workflows and planned once

### CI/CD

- [x] Build with Gradle and Push to GitHub registry/DockerHub/Quey  [build-gradle.yml](.github/workflows/build-gradle.yml)
- [x] Build Native Image with Gradle and Push to GitHub registry 
- [ ] Build with Maven and Push to GitHub registry 
- [x] Deploy image to Azure Kubernetes  
- [ ] Deploy image to AWS Kubernetes
- [ ] Deploy image to GCP Kubernetes
- [x] Deploy react app to GitHub Pages

### Terraform

- [x] Terraform workflow to select workspace, format, plan & apply Terraform code [terraform-plan-apply.yml](.github/workflows/terraform-plan-apply.yml)

### Quick Checks 

- [x] Quick checks for JUnits Spring Boot [quick-checks-unit.yml](.github/workflows/quick-checks-unit.yml)
- [x] Quick checks for Unit Tests Golang [quick-checks-unit-go.yml](.github/workflows/quick-checks-unit-go.yml)
- [x] Quick checks for SonarQube Static Code Analysis Gradle [quick-checks-sonar.yml](.github/workflows/quick-checks-sonar.yml)
- [x] Quick checks for SonarQube Static Code Analysis Go, Python, JS, TS, PHP etc [quick-checks-go.yml](.github/workflows/quick-checks-sonar-go.yml)
- [x] Quick checks for Datree K8s Configs Analysis [quick-checks-datree.yml](.github/workflows/quick-checks-datree.yml)

### Azure 
- [x] Deploy Java Gradle project to Azure Function Apps [deploy-functionapp-gradle.yml](.github/workflows/deploy-functionapp-gradle.yml)

### Other

- [x] Publish to Github Pages included in 1st and 2nd
- [ ] API Spec converter ( RAML, OAS2, OAS3 )
- [ ] API Spec rdme <https://github.com/readmeio/rdme>

- [ ] Lint code using [Super-Linter](https://github.com/super-linter/super-linter)
- [ ] Lint code using [MegaLinter](https://github.com/oxsecurity/megalinter)
- [ ] scans for dependency changes or vulnerabilities or invalid licenses using [DependencyReview](https://github.com/actions/dependency-review-action)
      requires `GitHub Advanced Security` license
