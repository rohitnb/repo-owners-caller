# Repo Owners Report

1. Copy this repository using the "Use this template" -> Create a new repository
![image](https://github.com/rohitnb/repo-owners-caller/assets/48172220/22f938ed-d4e7-4c83-bbd6-6279184f908c)

2. Create a new Personal Access Token and ensure it has `admin:org` permissions. Docs on creating a token can be found [here](https://docs.github.com/en/enterprise-cloud@latest/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic)
   
3. Authorize the token if you intend to use this with an SSO protected organization. Docs [here](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)

4. Navigate to Settings-> Secrets and Variables -> Actions -> New Repository Secret

5. Add the name as `ORG_TOKEN` and Secret as the token you generated in Steps 2 and 3
