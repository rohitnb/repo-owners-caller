# Repo Owners Report

## Prerequisites

- GitHub Personal Access Token with `admin:org` permissions and authorized to access the Orgs
    - [How to create one?](https://docs.github.com/en/enterprise-cloud@latest/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic)
    - If SSO is enabled for your orgs, then authorize the token to access them. [How do I authorize my personal access token?](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)

## Running the report

#### 1. Copy this repository using the "Use this template" -> Create a new repository

![image](https://github.com/rohitnb/repo-owners-caller/assets/48172220/22f938ed-d4e7-4c83-bbd6-6279184f908c)

#### 2. Navigate to Settings -> Secrets and Variables -> Actions -> New Repository Secret

<img width="1286" alt="Screenshot 2023-09-18 at 11 58 36 AM" src="https://github.com/rohitnb/repo-owners-caller/assets/48172220/c4799477-411b-4144-a4fb-be9059b13fa6">

#### 3. Add the personal access token you created with the name `ORG_TOKEN`. If you don't have a personal access token, follow the documents in the [Prerequisites](https://github.com/rohitnb/repo-owners-caller/tree/main#prerequisites) section

<img width="995" alt="Screenshot 2023-09-18 at 11 59 59 AM" src="https://github.com/rohitnb/repo-owners-caller/assets/48172220/111c9543-aac7-4962-8a8a-908d4005bf26">

#### 4. Navigate to the Actions tab -> Repo Owners Report -> Run Workflow -> Input the Org Name & click Run Workflow

<img width="1510" alt="Screenshot 2023-09-18 at 11 32 56 AM" src="https://github.com/rohitnb/repo-owners-caller/assets/48172220/5e4683a5-a5a5-478a-96ce-a4ced4603b6b">

#### 5. When it completes execution, you would be able to download the reports by clicking on the relevant run and clicking on the generated artifact

<img width="1489" alt="Screenshot 2023-09-18 at 11 52 39 AM" src="https://github.com/rohitnb/repo-owners-caller/assets/48172220/cb4c137f-8af6-4961-983c-060c34076eb9">

