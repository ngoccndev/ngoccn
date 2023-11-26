## Continuous Integration
### GitHub
The developers commit and push code to the GitHub repository which is linked to the CircleCI platform.
GitHub triggers the CircleCI platform when code is pushed to the repository.

### CircleCI
CircleCI reads the `.circleci/config.yml` file and run Jobs follow the config.
In the case Udagram the CircleCI will `build` after waiting approval and after approved `deploy` then the latest code will be deployed
