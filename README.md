# GitHub Security Quiz: 75 Questions with Answers

This README contains 75 questions related to GitHub security features, including Code Scanning, Secret Scanning, Dependabot, and more, along with their multiple-choice options and correct answers. Perfect for studying GitHub security concepts! 🚀

---

## Questions and Answers

### 1. By default, what is the minimum role needed to bypass push protection in a repository?
- A) Write
- B) Maintain
- C) Admin
- D) Triage

**Correct Answer**: Admin

---

### 2. What YAML syntax do you use to exclude certain files from secret scanning?
- A) paths-ignore
- B) decrypt_secret.sh
- C) branches-ignore
- D) secret_scanning.yml

**Correct Answer**: paths-ignore

---

### 3. Which of the following options would close a Dependabot alert?
- A) Viewing the dependency graph
- B) Leaving the repository in its current state
- C) Viewing the Dependabot alert on the Dependabot alerts tab
- D) Creating a pull request to resolve the vulnerability that will be approved and merged

**Correct Answer**: Creating a pull request to resolve the vulnerability that will be approved and merged

---

### 4. What action do you need to include in your workflow to upload a third-party Static Analysis Results Interchange Format (SARIF) file?
- A) dependency-review
- B) partialFingerprints
- C) upload-sarif
- D) scheduled

**Correct Answer**: upload-sarif

---

### 5. Which of the following formats are used to describe a code scanning alert from CodeQL?
- A) Common Vulnerabilities and Exposures (CVE)
- B) Common Weakness Enumeration (CWE)
- C) Vulnerability Exploitability eXchange (VEX)
- D) GitHub Security Advisory (GHSA)

**Correct Answer**: Common Weakness Enumeration (CWE)

---

### 6. What is code scanning?
- A) A feature that analyzes the code in a GitHub repository to find security vulnerabilities and coding errors
- B) A feature that scans repositories for known types of secrets
- C) A feature to identify all your project's dependencies
- D) A feature to privately discuss, fix, and publish information about security vulnerabilities

**Correct Answer**: A feature that analyzes the code in a GitHub repository to find security vulnerabilities and coding errors

---

### 7. Which of the following steps should you follow to integrate CodeQL into a third-party continuous integration system? (Choose three)
- A) Install the CLI
- B) Analyze code
- C) Process alerts
- D) Write queries
- E) Upload scan results

**Correct Answers**: Install the CLI, Analyze code, Upload scan results

---

### 8. Which of the following features can be used to enforce passing status checks for code scanning and dependency review?
- A) Insights
- B) Repository rulesets
- C) Security GuardRails
- D) Status enforcement

**Correct Answer**: Repository rulesets

---

### 9. Which of the following would raise secret scanning alerts?
- A) GitHub personal access token
- B) Server-side request forgery
- C) Cross site scripting (XSS)
- D) Structured query language (SQL) injection

**Correct Answer**: GitHub personal access token

---

### 10. What is the minimum role needed in order to view the secret scanning alerts list within the Security tab of a repository?
- A) Repository owner
- B) Read
- C) Write
- D) Admin

**Correct Answer**: Write

---

### 11. Where can a user change a repository's code scanning severity threshold that fails a pull request status check?
- A) Settings tab
- B) Pull Requests tab
- C) Actions tab
- D) Security tab

**Correct Answer**: Settings tab

---

### 12. Which of the following is the most proactive and practical way to prevent new secret scanning alerts?
- A) Enable push protection
- B) Scan for non-provider patterns
- C) Use feature branches
- D) Configure a secret scanning Actions workflow

**Correct Answer**: Enable push protection

---

### 13. Assuming there is no custom Dependabot behavior configured, where possible, what does Dependabot do after sending an alert about a vulnerability?
- A) Scans repositories for vulnerable dependencies on a schedule
- B) Scans any push to all branches
- C) Constructs a graph of all the repository's dependencies
- D) Creates a pull request to upgrade the vulnerable dependency to the minimum possible secure version

**Correct Answer**: Creates a pull request to upgrade the vulnerable dependency to the minimum possible secure version

---

### 14. As a developer with write access, you navigate to a code scanning alert in your repository. When will GitHub close this alert?
- A) After you fix the code by committing within the pull request
- B) When you use data-flow analysis
- C) After you find the code and click the alert
- D) After you triage the pull request

**Correct Answer**: After you fix the code by committing within the pull request

---

### 15. What is a security policy?
- A) A file in a GitHub repository that provides instructions to users about how to report a security vulnerability
- B) An automatic detection of security vulnerabilities
- C) An alert about dependencies with known vulnerabilities
- D) A security alert issued to a community

**Correct Answer**: A file in a GitHub repository that provides instructions to users about how to report a security vulnerability

---

### 16. Which GitHub security feature should you use to see details of any vulnerable dependency versions within a pull request?
- A) Dependabot alerts
- B) Dependency graph
- C) Dependency review
- D) Code scanning

**Correct Answer**: Dependency review

---

### 17. Which of the following is required to block the merge of a pull request containing critical vulnerabilities? (Choose two)
- A) Configure a CODEOWNERS file
- B) Add a repository ruleset
- C) Establish protection rules in the code security settings
- D) Enable Dependabot for the organization

**Correct Answers**: Add a repository ruleset, Establish protection rules in the code security settings

---

### 18. When secret scanning detects a set of credentials on a public repository, what does GitHub do?
- A) Sends a notification to repository members
- B) Notifies the service provider who issued the secret
- C) Scans the contents of the commits for additional secrets
- D) Displays a public alert in the Security tab

**Correct Answer**: Notifies the service provider who issued the secret

---

### 19. You have enabled security updates for a repository. When does GitHub mark a Dependabot alert as resolved?
- A) When you merge a pull request that contains a security update
- B) When you dismiss the Dependabot alert
- C) When the pull request checks are successful
- D) When Dependabot creates a pull request

**Correct Answer**: When you merge a pull request that contains a security update

---

### 20. What is required to trigger code scanning on a specified branch?
- A) The repository must be private
- B) Secret scanning must be enabled
- C) The workflow file must exist in that branch
- D) Developers must actively maintain the repository

**Correct Answer**: The workflow file must exist in that branch

---

### 21. What is the best method to ensure all new code is scanned for vulnerabilities?
- A) Add the extended suite
- B) Configure code scanning
- C) Configure code owners
- D) Set up a security policy

**Correct Answer**: Configure code scanning

---

### 22. How many alerts are created when two instances of the same secret value are in the same repository?
- A) 1
- B) 2
- C) 3
- D) 4

**Correct Answer**: 1

---

### 23. Assuming that no custom Dependabot behavior is configured, who has the ability to merge a pull request created via Dependabot?
- A) A user who has write access to the repository
- B) A user who has read access to the repository
- C) A repository member of an enterprise organization
- D) An enterprise administrator

**Correct Answer**: A user who has write access to the repository

---

### 24. Where is secret scanning enabled on a private repository?
- A) Within a secret.yml file
- B) Within a repository ruleset
- C) In the code scanning default setup settings
- D) In the code security settings

**Correct Answer**: In the code security settings

---

### 25. Where can you find the vulnerable dependencies that GitHub detected in your repository?
- A) In security advisories
- B) In code scanning alerts
- C) In Dependabot alerts
- D) In secret scanning alerts

**Correct Answer**: In Dependabot alerts

---

### 26. The autobuild step in the CodeQL workflow has failed. What should you do?
- A) Remove specific build steps
- B) Use CodeQL, which implicitly detects supported languages
- C) Remove the autobuild step and add specific build steps
- D) Compile the source code

**Correct Answer**: Remove the autobuild step and add specific build steps

---

### 27. Which key is required in the update settings of the Dependabot configuration file?
- A) Assignees
- B) Package-ecosystem
- C) Rebase-strategy
- D) Commit-message

**Correct Answer**: Package-ecosystem

---

### 28. Which of the following verifies if a secret is active and has not been revoked?
- A) Push protection
- B) Branch protection
- C) Validity checks
- D) Custom patterns

**Correct Answer**: Validity checks

---

### 29. If a line of code containing a secret is deleted, where can it still be found?
- A) Issues
- B) Insights
- C) Commits
- D) Dependency graph

**Correct Answer**: Commits

---

### 30. Which of the following is the best way to dispose of a compromised secret?
- A) Create a new secret
- B) Revoke the secret
- C) Remove the secret from the code base
- D) Update any services that use the secret

**Correct Answer**: Revoke the secret

---

### 31. What is the best way to ensure that added dependencies' licenses are checked and new code is analyzed at the repository level?
- A) Configure a workflow with the dependency review action
- B) Enable secret scanning
- C) Configure Require status checks with a CodeQL action
- D) Configure Dependabot

**Correct Answer**: Configure a workflow with the dependency review action

---

### 32. What classification is used to categorize Dependabot alerts? (Choose three)
- A) Static Application Security Testing (SAST)
- B) Exploit Prediction Scoring System (EPSS)
- C) Common Vulnerabilities and Exposures (CVE)
- D) GitHub Security Advisory ID (GHSA)
- E) Common Weakness Enumeration (CWE)

**Correct Answers**: Common Vulnerabilities and Exposures (CVE), GitHub Security Advisory ID (GHSA), Common Weakness Enumeration (CWE)

---

### 33. Secret scanning will ignore a secret_scanning.yml file that:
- A) Is 100 KB or larger
- B) Contains 1,000 or more entries
- C) Has 1,000 or more directories
- D) Is 1 MB or larger

**Correct Answer**: Is 1 MB or larger

---

### 34. A repository's dependency graph includes:
- A) Annotated code scanning alerts from your repository's dependencies
- B) Dependencies parsed from a repository's manifest and lock files
- C) Dependencies from all your repositories
- D) A summary of the dependencies used in your organization's repositories

**Correct Answer**: Dependencies parsed from a repository's manifest and lock files

---

### 35. Which of the following benefits do code scanning, secret scanning, and dependency review provide?
- A) View alerts about dependencies with known vulnerabilities
- B) Confidentially report and discuss security vulnerabilities
- C) Search for potential security vulnerabilities, detect secrets, and show the impact of dependency changes
- D) Automatically raise pull requests to reduce exposure

**Correct Answer**: Search for potential security vulnerabilities, detect secrets, and show the impact of dependency changes

---

### 36. Where in the repository can you give additional users access to secret scanning alerts?
- A) Secrets
- B) Security
- C) Settings
- D) Insights

**Correct Answer**: Settings

---

### 37. What does a CodeQL database of your repository contain?
- A) Build commands for C/C++, C#, and Java
- B) A representation of all of the source code
- C) A build for Go projects to set up the project
- D) A build of the code and extracted data

**Correct Answer**: A build of the code and extracted data

---

### 38. When using CodeQL, how does extraction for compiled languages work?
- A) By monitoring the normal build process
- B) By generating one language at a time
- C) By resolving dependencies to give an accurate representation
- D) By running directly on the source code

**Correct Answer**: By monitoring the normal build process

---

### 39. Which features require GitHub Advanced Security to be enabled for internal and private repositories? (Choose two)
- A) Packages
- B) Secret scanning
- C) Security policy
- D) Dependency review

**Correct Answers**: Secret scanning, Dependency review

---

### 40. Which of the following pre-defined roles is required to manage code scanning alerts in a repository?
- A) View
- B) Triage
- C) Read
- D) Maintain

**Correct Answer**: Triage

---

### 41. You are configuring code scanning with CodeQL. What is one impact of using a language matrix in your workflow?
- A) CodeQL will only analyze the languages in the matrix
- B) You can use the languages parameter under the init action
- C) CodeQL excludes alerts for dependencies specified in the matrix
- D) CodeQL is configured to run analysis sequentially

**Correct Answer**: You can use the languages parameter under the init action

---

### 42. When using the advanced CodeQL code scanning setup, what is the name of the workflow file?
- A) codeql-config.yml
- B) codeql-workflow.yml
- C) codeql-scan.yml
- D) codeql.yml

**Correct Answer**: codeql.yml

---

### 43. When configuring code scanning with CodeQL, what are your options for specifying additional queries? (Choose two)
- A) github/codeql
- B) Packs
- C) Queries
- D) Scope

**Correct Answers**: Packs, Queries

---

### 44. To be compatible with code scanning, what data format must third-party code scanning tools use for output?
- A) Static Analysis Results Interchange Format (SARIF)
- B) YAML
- C) Comma separated values (CSV)
- D) ESLint

**Correct Answer**: Static Analysis Results Interchange Format (SARIF)

---

### 45. Which syntax in a query suite tells CodeQL to look for one or more specified .ql files?
- A) qls
- B) qlpack
- C) query
- D) suite

**Correct Answer**: query

---

### 46. By default, which roles can enable Dependabot alerts?
- A) Outside collaborators
- B) Security analysts
- C) Repository maintainers
- D) Repository administrators

**Correct Answer**: Repository administrators

---

### 47. You are creating an application that will utilize the code scanning API to export a repository's alerts. Which scope must be included in the GitHub token?
- A) CCC workflow
- B) read:user
- C) security_events
- D) admin:org

**Correct Answer**: security_events

---

### 48. By default, where will secret scanning look in a repository in order to execute its job? (Choose three)
- A) All files in the repository
- B) Selected files in the repository
- C) Dependencies
- D) Full commit history
- E) All branches

**Correct Answers**: All files in the repository, Full commit history, All branches

---

### 49. What scenario demonstrates the use of Dependabot security updates?
- A) A pull request is opened that updates a dependency to the most recent version
- B) An alert is created for a vulnerable dependency
- C) An alert is created for a secret that's been exposed
- D) A pull request is opened that fixes a vulnerable dependency

**Correct Answer**: A pull request is opened that fixes a vulnerable dependency

---

### 50. Which of the following verifies if a secret is active and has not been revoked?
- A) Push protection
- B) Branch protection
- C) Validity checks
- D) Custom patterns

**Correct Answer**: Validity checks

---

### 51. If a line of code containing a secret is deleted, where can it still be found?
- A) Issues
- B) Insights
- C) Commits
- D) Dependency graph

**Correct Answer**: Commits

---

### 52. Which of the following is the best way to dispose of a compromised secret?
- A) Create a new secret
- B) Revoke the secret
- C) Remove the secret from the code base
- D) Update any services that use the secret

**Correct Answer**: Revoke the secret

---

### 53. What is the best way to ensure that added dependencies' licenses are checked and new code is analyzed at the repository level?
- A) Configure a workflow with the dependency review action
- B) Enable secret scanning
- C) Configure Require status checks with a CodeQL action
- D) Configure Dependabot

**Correct Answer**: Configure a workflow with the dependency review action

---

### 54. What classification is used to categorize Dependabot alerts? (Choose three)
- A) Static Application Security Testing (SAST)
- B) Exploit Prediction Scoring System (EPSS)
- C) Common Vulnerabilities and Exposures (CVE)
- D) GitHub Security Advisory ID (GHSA)
- E) Common Weakness Enumeration (CWE)

**Correct Answers**: Common Vulnerabilities and Exposures (CVE), GitHub Security Advisory ID (GHSA), Common Weakness Enumeration (CWE)

---

### 55. Secret scanning will ignore a secret_scanning.yml file that:
- A) Is 100 KB or larger
- B) Contains 1,000 or more entries
- C) Has 1,000 or more directories
- D) Is 1 MB or larger

**Correct Answer**: Is 1 MB or larger

---

### 56. A repository's dependency graph includes:
- A) Annotated code scanning alerts from your repository's dependencies
- B)Dependencies parsed from a repository's manifest and lock files
- C) Dependencies from all your repositories
- D) A summary of the dependencies used in your organization's repositories

**Correct Answer**: Dependencies parsed from a repository's manifest and lock files

---

### 57. Which of the following benefits do code scanning, secret scanning, and dependency review provide?
- A) View alerts about dependencies with known vulnerabilities
- B) Confidentially report and discuss security vulnerabilities
- C) Search for potential security vulnerabilities, detect secrets, and show the impact of dependency changes
- D) Automatically raise pull requests to reduce exposure

**Correct Answer**: Search for potential security vulnerabilities, detect secrets, and show the impact of dependency changes

---

### 58. Where in the repository can you give additional users access to secret scanning alerts?
- A) Secrets
- B) Security
- C) Settings
- D) Insights

**Correct Answer**: Settings

---

### 59. What does a CodeQL database of your repository contain?
- A) Build commands for C/C++, C#, and Java
- B) A representation of all of the source code
- C) A build for Go projects to set up the project
- D) A build of the code and extracted data

**Correct Answer**: A build of the code and extracted data

---

### 60. When using CodeQL, how does extraction for compiled languages work?
- A) By monitoring the normal build process
- B) By generating one language at a time
- C) By resolving dependencies to give an accurate representation
- D) By running directly on the source code

**Correct Answer**: By monitoring the normal build processandria

---

### 61. Which features require GitHub Advanced Security to be enabled for internal and private repositories? (Choose two)
- A) Packages
- B) Secret scanning
- C) Security policy
- D) Dependency review

**Correct Answers**: Secret scanning, Dependency review

---

### 62. Which of the following pre-defined roles is required to manage code scanning alerts in a repository?
- A) View
- B) Triage
- C) Read
- D) Maintain

**Correct Answer**: Triage

---

### 63. You are configuring code scanning with CodeQL. What is one impact of using a language matrix in your workflow?
- A) CodeQL will only analyze the languages in the matrix
- B) You can use the languages parameter under the init action
- C) CodeQL excludes alerts for dependencies specified in the matrix
- D) CodeQL is configured to run analysis sequentially

**Correct Answer**: You can use the languages parameter under the init action

---

### 64. When using the advanced CodeQL code scanning setup, what is the name of the workflow file?
- A) codeql-config.yml
- B) codeql-workflow.yml
- C) codeql-scan.yml
- D) codeql.yml

**Correct Answer**: codeql.yml

---

### 65. When configuring code scanning with CodeQL, what are your options for specifying additional queries? (Choose two)
- A) github/codeql
- B) Packs
- C) Queries
- D) Scope

**Correct Answers**: Packs, Queries

---

### 66. To be compatible with code scanning, what data format must third-party code scanning tools use for output?
- A) Static Analysis Results Interchange Format (SARIF)
- B) YAML
- C) Comma separated values (CSV)
- D) ESLint

**Correct Answer**: Static Analysis Results Interchange Format (SARIF)

---

### 67. Which syntax in a query suite tells CodeQL to look for one or more specified .ql files?
- A) qls
- B) qlpack
- C) query
- D) suite

**Correct Answer**: query

---

### 68. By default, which roles can enable Dependabot alerts?
- A) Outside collaborators
- B) Security analysts
- C) Repository maintainers
- D) Repository administrators

**Correct Answer**: Repository administrators

---

### 69. You are creating an application that will utilize the code scanning API to export a repository's alerts. Which scope must be included in the GitHub token?
- A) CCC workflow
- B) read:user
- C) security_events
- D) admin:org

**Correct Answer**: security_events

---

### 70. By default, where will secret scanning look in a repository in order to execute its job? (Choose three)
- A) All files in the repository
- B) Selected files in the repository
- C) Dependencies
- D) Full commit history
- E) All branches

**Correct Answers**: All files in the repository, Full commit history, All branches

---

### 71. What scenario demonstrates the use of Dependabot security updates?
- A) A pull request is opened that updates a dependency to the most recent version
- B) An alert is created for a vulnerable dependency
- C) An alert is created for a secret that's been exposed
- D) A pull request is opened that fixes a vulnerable dependency

**Correct Answer**: A pull request is opened that fixes a vulnerable dependency

---

### 72. Which of the following verifies if a secret is active and has not been revoked?
- A) Push protection
- B) Branch protection
- C) Validity checks
- D) Custom patterns

**Correct Answer**: Validity checks

---

### 73. If a line of code containing a secret is deleted, where can it still be found?
- A) Issues
- B) Insights
- C) Commits
- D) Dependency graph

**Correct Answer**: Commits

---

### 74. Which of the following is the best way to dispose of a compromised secret?
- A) Create a new secret
- B) Revoke the secret
- C) Remove the secret from the code base
agemaker
- D) Update any services that use the secret

**Correct Answer**: Revoke the secret

---

### 75. What is the best way to ensure that added dependencies' licenses are checked and new code is analyzed at the repository level?
- A) Configure a workflow with the dependency review action
- B) Enable secret scanning
- C) Configure Require status checks with a CodeQL action
- D) Configure Dependabot

**Correct Answer**: Configure a workflow with the dependency review action
