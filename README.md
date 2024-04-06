# Reusable Workflows repo 

### Included working workflows and planned once

### CI/CD

- [x] Build with Gradle and Push to GitHub registry/DockerHub/Quey  [build-gradle.yaml](.github/workflows/build-gradle.yaml)
- [x] Build Native Image with Gradle and Push to GitHub registry 
- [ ] Build with Maven and Push to GitHub registry 
- [x] Deploy image to Azure Kubernetes  
- [ ] Deploy image to AWS Kubernetes
- [ ] Deploy image to GCP Kubernetes
- [x] Deploy react app to GitHub Pages

### Terraform

- [x] Terraform workflow to select workspace, format, plan & apply Terraform code [terraform-plan-apply.yaml](.github/workflows/terraform-plan-apply.yaml)

### Quick Checks 

- [x] Quick checks for JUnits Spring Boot [quick-checks-unit.yaml](.github/workflows/quick-checks-unit.yaml)
- [x] Quick checks for Unit Tests Golang [quick-checks-unit-go.yaml](.github/workflows/quick-checks-unit-go.yaml)
- [x] Quick checks for SonarQube Static Code Analysis Gradle [quick-checks-sonar.yaml](.github/workflows/quick-checks-sonar.yaml)
- [x] Quick checks for SonarQube Static Code Analysis Go, Python, JS, TS, PHP etc [quick-checks-go.yaml](.github/workflows/quick-checks-sonar-go.yaml)
- [x] Quick checks for Datree K8s Configs Analysis [quick-checks-datree.yaml](.github/workflows/quick-checks-datree.yaml)

### Azure 
- [x] Deploy Java Gradle project to Azure Function Apps [deploy-functionapp-gradle.yaml](.github/workflows/deploy-functionapp-gradle.yaml)

### Other

- [x] Publish to Github Pages included in 1st and 2nd
- [ ] API Spec converter ( RAML, OAS2, OAS3 )
- [ ] API Spec rdme <https://github.com/readmeio/rdme>

- [ ] Lint code using [Super-Linter](https://github.com/super-linter/super-linter)
- [ ] Lint code using [MegaLinter](https://github.com/oxsecurity/megalinter)
- [ ] scans for dependency changes or vulnerabilities or invalid licenses using [DependencyReview](https://github.com/actions/dependency-review-action)
      requires `GitHub Advanced Security` license
