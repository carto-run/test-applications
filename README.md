# test-applications

This repo lists all test applications / workloads within the carto-run org.

| Application | Language | Source Tester | Image Builder | Should Pass | Comments |
| ----------- | -------- | ------------- | ------------- | ----------- | -------- |
| [app-maven-kaniko](https://github.com/carto-run/app-maven-kaniko) | java | tekton | kaniko | ✅ | |
| [app-maven-kaniko-fails-at-image-build](https://github.com/carto-run/app-maven-kaniko-fails-at-image-build) | java | tekton | kaniko | fails at Image Provider | kaniko build fails but invalid status is reported |
| [app-maven-kaniko-with-subpath](https://github.com/carto-run/app-maven-kaniko-with-subpath) | java | tekton | kaniko | ✅ | incorrectly fails at the source tester stage |
| [app-maven-kpack](https://github.com/carto-run/app-maven-kpack) | java | tekton | tbs | ✅ | |
| [app-maven-kpack-fails-at-image-build](https://github.com/carto-run/app-maven-kpack-fails-at-image-build) | java | tekton | tbs | fails at Image Provider | kpack build fails but stage is reported as success |
| [app-maven-kpack-with-subpath](https://github.com/carto-run/app-maven-kpack-with-subpath) | java | tekton | tbs | ✅ | incorrectly fails at the source tester stage |
| [app-maven-fails-at-source-tester](https://github.com/carto-run/app-maven-fails-at-source-tester) | java | tekton | - | fails at Source Tester | |
| [app-maven-jenkins-kpack](https://github.com/carto-run/app-maven-jenkins-kpack) | java | tekton & jenkins | tbs | ✅ | |
| [app-maven-jenkins-fails-at-source-tester](https://github.com/carto-run/app-maven-jenkins-fails-at-source-tester) | java | tekton & jenkins | - | fails at Source Test | |
| [app-maven-fails-at-source-scan](https://github.com/carto-run/app-maven-fails-at-source-scan) | java | tekton | - | fails at Source Scan | |
| [app-maven-kpack-fails-at-image-scan](https://github.com/carto-run/app-maven-kpack-fails-at-image-scan) | java | tekton | tbs | fails at Image Scan | |
| [app-image](https://github.com/carto-run/app-image) | java | - | pack-cli | ✅ | |
| [app-mavenartifact](https://github.com/carto-run/app-mavenartifact) | java | tekton (noop) | tbs | ✅ | |
| [app-mavenartifact-fails-at-source-provider](https://github.com/carto-run/app-mavenartifact/blob/main/README.md#simulating-a-broken-source-provider) | - | - | - | fails at Source Provider | |
