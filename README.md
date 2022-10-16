# github-actions-test

##### build the project

- `./gradlew build`

##### build Docker image called github-actions-test. Execute from root

- `docker build -t github-actions-test .`

##### push image to repo

- `docker tag github-actions-test batiuszkamaroz/github-actions-test:1.0`
- `docker push batiuszkamaroz/github-actions-test:1.0`
