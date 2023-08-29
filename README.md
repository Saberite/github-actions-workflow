# github-actions-workflow

## Setting up GitHub Personal Access Token
### Generating GitHub Personal Access Token
Our GitHub Action workflow needs to call the GitHub API to create a GitHub repository and push code to the repository. In order to call the GitHub API it needs the GitHub Personal Access Token.

Click on your `GitHub Profile` (on the upper right corner), then select `settings` on the drop down menu, then select `Developer settings` on the lower right corner. Now you are on the Developers Setting page, select `Fine-grained tokens` then click on `Generate a personal access token`.

![alt text](https://github.com/yilenayao/github-actions-workflow/media/images/.img)
![alt text](https://github.com/yilenayao/github-actions-workflow/media/images/.img)

Provide a `Token name`, set an `Expiration` date, for `Repository access` select All Repositories.

For `Permissions` you need to set `Read and Write` access for

Administration
- Contents
- Secrets
- Workflows
Please save you GitHub Personal Access Token.

### Setting up Github Secrets
On your GitHub repository go to `Settings` then `Secrets and variables`, then click `Actions`
![alt text](https://github.com/yilenayao/github-actions-workflow/media/images/.img)

## Creating Spring Boot Project with Github Actions
In your GitHub repository containing the GitHub Action, click on the `Actions` tab, then click on Clock on `Run workflow`, then fill in all the fields and then click `Run workflow`.
![alt text](https://github.com/yilenayao/github-actions-workflow/media/images/.img)
Congrats, your Spring Boot application has been created.

