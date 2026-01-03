# github_CICD
[It is uploaded repository that is why    github_CICD/.github/workflows
/build.yml    for Original repository: jenkinsCICD/.github/workflows
/build.yml
]
Does your app start locally?
Examples:
Spring Boot → ./gradlew bootRun (Run locally)
Node.js → npm start
Docker → docker-compose 


Step 1: Create GitHub PAT (only once)
Even in same account, private repos need token.
GitHub → Settings
Developer settings → Personal access tokens
Generate token with:
✅ repo
Copy token
Go to automation repo → Settings → Secrets

Add:

Name: APP_REPO_TOKEN
Value: <your_token>
