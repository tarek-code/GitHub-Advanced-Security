# GitHub Security & Code Scanning – 75 Questions with Answers

### 1. By default, what is the minimum role needed to bypass push protection in a repository?
**Answer:** Admin

### 2. What YAML syntax do you use to exclude certain files from secret scanning?
**Answer:** paths-ignore:

### 3. Which of the following options would close a Dependabot alert?
**Answer:** creating a pull request to resolve the vulnerability that will be approved and merged

### 4. What action do you need to include in your workflow to upload a third-party Static Analysis Results Interchange Format (SARIF) file
**Answer:** upload-sarif

### 5. Which of the following formats are used to describe a code scanning alert from CodeQL?
**Answer:** Common Weakness Enumeration (CWE)

### 6. What is code scanning?
**Answer:** a feature that analyzes the code in a GitHub repository to find security vulnerabilities and coding errors

### 7. Which of the following steps should you follow to integrate CodeQL into a third-party continuous integration system?
**Answer:** install the CLI, analyze code, upload scan results

### 8. Which of the following features can be used to enforce passing status checks for code scanning and dependency review workflows?
**Answer:** repository rulesets

### 9. Which of the following would raise secret scanning alerts?
**Answer:** GitHub personal access token

### 10. What is the minimum role needed in order to view the secret scanning alerts list within the Security tab of a repository?
**Answer:** Write

### 11. Where can a user change a repository's code scanning severity threshold that fails a pull request status check?
**Answer:** Security tab

### 12. Which of the following is the most proactive and practical way to prevent new secret scanning alerts?
**Answer:** Enable push protection.

### 13. Assuming there is no custom Dependabot behavior configured, where possible, what does Dependabot do after sending an alert about a vulnerability?
**Answer:** creates a pull request to upgrade the vulnerable dependency to the minimum possible secure version

### 14. As a developer with write access, you navigate to a code scanning alert in your repository. When will GitHub close this alert?
**Answer:** after you fix the code by committing within the pull request

### 15. What is a security policy?
**Answer:** a file in a GitHub repository that provides instructions to users about how to report a security vulnerability

### 16. Which GitHub security feature should you use to see details of any vulnerable dependency versions within a pull request?
**Answer:** dependency review

### 17. Which of the following is required to block the merge of a pull request containing critical vulnerabilities?
**Answer:** Add a repository ruleset, Establish the protection rules in the code security settings

### 18. When secret scanning detects a set of credentials on a public repository, what does GitHub do?
**Answer:** It notifies the service provider who issued the secret.

### 19. You have enabled security updates for a repository. When does GitHub mark a Dependabot alert as resolved for that repo?
**Answer:** when you merge a pull request that contains a security update

### 20. What is required to trigger code scanning on a specified branch?
**Answer:** The workflow file must exist in that branch.

### 21. What is the best method to ensure all new code is scanned for vulnerabilities?
**Answer:** Configure code scanning.

### 22. How many alerts are created when two instances of the same secret value are in the same repository?
**Answer:** 1

### 23. Assuming that no custom Dependabot behavior is configured, who has the ability to merge a pull request created via Dependabot?
**Answer:** a user who has write access to the repository

### 24. Where is secret scanning enabled on a private repository?
**Answer:** in the code security settings

### 25. Where can you find the vulnerable dependencies that GitHub detected in your repository?
**Answer:** in Dependabot alerts

### 26. The autobuild step in the CodeQL workflow has failed. What should you do?
**Answer:** Remove the autobuild step from your code scanning workflow and add specific build steps.

### 27. Which key is required in the update settings of the Dependabot configuration file?
**Answer:** package-ecosystem

### 28. You are a maintainer of a repository and Dependabot notifies you of a vulnerability. Where could the vulnerability be?
**Answer:** in manifest and lock files, in security advisories reported on GitHub

### 29. What is the purpose of push protection?
**Answer:** to scan and block the code that contains secrets before it reaches the repository

### 30. Which details do you have to provide to create a custom pattern for secret scanning?
**Answer:** the secret format, the name of the pattern

### 31. You have enabled Dependabot alerts on your repository. If Dependabot detects a vulnerable dependency, it sends an alert when:
**Answer:** a contributor adds the vulnerable dependency to a manifest in the repository.

### 32. By default, who will receive an e-mail when a secret has been detected in a repository?
**Answer:** users with the Admin repository role, user who committed the secret

### 33. What kind of repository permissions do you need to request a Common Vulnerabilities and Exposures (CVE) identification?
**Answer:** Admin

### 34. Using advanced setup, which code scanning configuration would help detect vulnerabilities before they are added to a shared branch?
**Answer:** on: pull_request

### 35. When secret scanning is enabled by default, what does it scan?
**Answer:** all files in the repository, full commit history, all branches

### 36. A colleague ignores a code scanning alert. What are the implications?
**Answer:** Sensitive information could be leaked, A dangerous argument could be passed to functions, Data could be used insecurely.

### 37. What happens when you enable secret scanning on a private repository?
**Answer:** GitHub performs a read-only analysis on the repository.

### 38. What details should you include in your security policy?
**Answer:** how to report a vulnerability

### 39. After looking into an injection code scanning alert, you notice that the input is properly sanitized with custom logic. What should you do?
**Answer:** Dismiss the alert with the reason "false positive."

### 40. Assuming that no custom patterns are configured, what type of secret is detected by secret scanning?
**Answer:** private keys

### 41. You are configuring a CodeQL workflow for compiled languages. What happens if your workflow uses a language matrix?
**Answer:** You can use the languages parameter under the init action.

### 42. When using the advanced CodeQL code scanning setup, what is the name of the workflow file?
**Answer:** codeql.yml

### 43. When configuring code scanning with CodeQL, what are your options for specifying additional queries?
**Answer:** packs, queries

### 44. To be compatible with code scanning, what data format must third-party code scanning tools use for output?
**Answer:** Static Analysis Results Interchange Format (SARIF)

### 45. Which syntax in a query suite tells CodeQL to look for one or more specified .ql files?
**Answer:** query

### 46. By default, which roles can enable Dependabot alerts?
**Answer:** repository administrators

### 47. You are creating an application that will utilize the code scanning application programming interface (API) to export a repo included in the GitHub token?
**Answer:** security_events

### 48. Which scenario demonstrates the use of Dependabot security updates?
**Answer:** A pull request is opened that fixes a vulnerable dependency.

