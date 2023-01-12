# test-applications

This repo lists all test applications / workloads within the carto-run org.

| Application | Language | Source Tester | Image Builder | Status |
| ----------- | -------- | ------------- | ------------- | ------ |
| [app-maven-kaniko](https://github.com/carto-run/app-maven-kaniko) | java | tekton | kaniko | ✅ |
| [app-maven-kaniko-fails-at-image-build](https://github.com/carto-run/app-maven-kaniko-fails-at-image-build) | java | tekton | kaniko | fails at Image Provider |
| [app-maven-kpack](https://github.com/carto-run/app-maven-kpack) | java | tekton | tbs | ✅ |
| [app-maven-kpack-fails-at-image-build](https://github.com/carto-run/app-maven-kpack-fails-at-image-build) | java | tekton | tbs | fails at Image Provider |
| [app-maven-fails-at-source-tester](https://github.com/carto-run/app-maven-fails-at-source-tester) | java | tekton | - | fails at Source Tester |
| [app-maven-jenkins-kpack](https://github.com/carto-run/app-maven-jenkins-kpack) | java | tekton & jenkins | tbs | ✅ |
