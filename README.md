# 🛡️ GitHub Security & Code Scanning – 75 Questions with Answers

هذا الملف يحتوي على **٧٥ سؤال وإجابته** خاصة بميزات الأمان في GitHub مثل:
- Code Scanning
- Dependabot
- Secret Scanning
- GitHub API permissions

---

## 📋 قائمة الأسئلة والإجابات:

### ❓ سؤال 1: By default, what is the minimum role needed to bypass push protection in a repository?
**✅ الإجابة:** `Admin`

### ❓ سؤال 2: What YAML syntax do you use to exclude certain files from secret scanning?
**✅ الإجابة:** `paths-ignore:`

### ❓ سؤال 3: Which of the following options would close a Dependabot alert?
**✅ الإجابة:** `creating a pull request to resolve the vulnerability that will be approved and merged`

### ❓ سؤال 4: What action do you need to include in your workflow to upload a third-party Static Analysis Results Interchange Format (SARIF) file
**✅ الإجابة:** `upload-sarif`

### ❓ سؤال 5: Which of the following formats are used to describe a code scanning alert from CodeQL?
**✅ الإجابة:** `Common Weakness Enumeration (CWE)`

### ❓ سؤال 6: What is code scanning?
**✅ الإجابة:** `a feature that analyzes the code in a GitHub repository to find security vulnerabilities and coding errors`

### ❓ سؤال 7: Which of the following steps should you follow to integrate CodeQL into a third-party continuous integration system?
**✅ الإجابة:** `install the CLI, analyze code, upload scan results`

### ❓ سؤال 8: Which of the following features can be used to enforce passing status checks for code scanning and dependency review workflows?
**✅ الإجابة:** `repository rulesets`

### ❓ سؤال 9: Which of the following would raise secret scanning alerts?
**✅ الإجابة:** `GitHub personal access token`

### ❓ سؤال 10: What is the minimum role needed in order to view the secret scanning alerts list within the Security tab of a repository?
**✅ الإجابة:** `Write`

### ❓ سؤال 11: Where can a user change a repository's code scanning severity threshold that fails a pull request status check?
**✅ الإجابة:** `Security tab`

### ❓ سؤال 12: Which of the following is the most proactive and practical way to prevent new secret scanning alerts?
**✅ الإجابة:** `Enable push protection.`

### ❓ سؤال 13: Assuming there is no custom Dependabot behavior configured, where possible, what does Dependabot do after sending an alert about a vulnerability?
**✅ الإجابة:** `creates a pull request to upgrade the vulnerable dependency to the minimum possible secure version`

### ❓ سؤال 14: As a developer with write access, you navigate to a code scanning alert in your repository. When will GitHub close this alert?
**✅ الإجابة:** `after you fix the code by committing within the pull request`

### ❓ سؤال 15: What is a security policy?
**✅ الإجابة:** `a file in a GitHub repository that provides instructions to users about how to report a security vulnerability`

### ❓ سؤال 16: Which GitHub security feature should you use to see details of any vulnerable dependency versions within a pull request?
**✅ الإجابة:** `dependency review`

### ❓ سؤال 17: Which of the following is required to block the merge of a pull request containing critical vulnerabilities?
**✅ الإجابة:** `Add a repository ruleset, Establish the protection rules in the code security settings`

### ❓ سؤال 18: When secret scanning detects a set of credentials on a public repository, what does GitHub do?
**✅ الإجابة:** `It notifies the service provider who issued the secret.`

### ❓ سؤال 19: You have enabled security updates for a repository. When does GitHub mark a Dependabot alert as resolved for that repo?
**✅ الإجابة:** `when you merge a pull request that contains a security update`

### ❓ سؤال 20: What is required to trigger code scanning on a specified branch?
**✅ الإجابة:** `The workflow file must exist in that branch.`

### ❓ سؤال 21: What is the best method to ensure all new code is scanned for vulnerabilities?
**✅ الإجابة:** `Configure code scanning.`

### ❓ سؤال 22: How many alerts are created when two instances of the same secret value are in the same repository?
**✅ الإجابة:** `1`

### ❓ سؤال 23: Assuming that no custom Dependabot behavior is configured, who has the ability to merge a pull request created via Dependabot?
**✅ الإجابة:** `a user who has write access to the repository`

### ❓ سؤال 24: Where is secret scanning enabled on a private repository?
**✅ الإجابة:** `in the code security settings`

### ❓ سؤال 25: Where can you find the vulnerable dependencies that GitHub detected in your repository?
**✅ الإجابة:** `in Dependabot alerts`

### ❓ سؤال 26: The autobuild step in the CodeQL workflow has failed. What should you do?
**✅ الإجابة:** `Remove the autobuild step from your code scanning workflow and add specific build steps.`

### ❓ سؤال 27: Which key is required in the update settings of the Dependabot configuration file?
**✅ الإجابة:** `package-ecosystem`

### ❓ سؤال 28: You are a maintainer of a repository and Dependabot notifies you of a vulnerability. Where could the vulnerability be?
**✅ الإجابة:** `in manifest and lock files, in security advisories reported on GitHub`

### ❓ سؤال 29: What is the purpose of push protection?
**✅ الإجابة:** `to scan and block the code that contains secrets before it reaches the repository`

### ❓ سؤال 30: Which details do you have to provide to create a custom pattern for secret scanning?
**✅ الإجابة:** `the secret format, the name of the pattern`

### ❓ سؤال 31: You have enabled Dependabot alerts on your repository. If Dependabot detects a vulnerable dependency, it sends an alert when:
**✅ الإجابة:** `a contributor adds the vulnerable dependency to a manifest in the repository.`

### ❓ سؤال 32: By default, who will receive an e-mail when a secret has been detected in a repository?
**✅ الإجابة:** `users with the Admin repository role, user who committed the secret`

### ❓ سؤال 33: What kind of repository permissions do you need to request a Common Vulnerabilities and Exposures (CVE) identification?
**✅ الإجابة:** `Admin`

### ❓ سؤال 34: Using advanced setup, which code scanning configuration would help detect vulnerabilities before they are added to a shared branch?
**✅ الإجابة:** `on: pull_request`

### ❓ سؤال 35: When secret scanning is enabled by default, what does it scan?
**✅ الإجابة:** `all files in the repository, full commit history, all branches`

### ❓ سؤال 36: A colleague ignores a code scanning alert. What are the implications?
**✅ الإجابة:** `Sensitive information could be leaked, A dangerous argument could be passed to functions, Data could be used insecurely.`

### ❓ سؤال 37: What happens when you enable secret scanning on a private repository?
**✅ الإجابة:** `GitHub performs a read-only analysis on the repository.`

### ❓ سؤال 38: What details should you include in your security policy?
**✅ الإجابة:** `how to report a vulnerability`

### ❓ سؤال 39: After looking into an injection code scanning alert, you notice that the input is properly sanitized with custom logic. What should you do?
**✅ الإجابة:** `Dismiss the alert with the reason "false positive."`

### ❓ سؤال 40: Assuming that no custom patterns are configured, what type of secret is detected by secret scanning?
**✅ الإجابة:** `private keys`

### ❓ سؤال 41: You are configuring a CodeQL workflow for compiled languages. What happens if your workflow uses a language matrix?
**✅ الإجابة:** `You can use the languages parameter under the init action.`

### ❓ سؤال 42: When using the advanced CodeQL code scanning setup, what is the name of the workflow file?
**✅ الإجابة:** `codeql.yml`

### ❓ سؤال 43: When configuring code scanning with CodeQL, what are your options for specifying additional queries?
**✅ الإجابة:** `packs, queries`

### ❓ سؤال 44: To be compatible with code scanning, what data format must third-party code scanning tools use for output?
**✅ الإجابة:** `Static Analysis Results Interchange Format (SARIF)`

### ❓ سؤال 45: Which syntax in a query suite tells CodeQL to look for one or more specified .ql files?
**✅ الإجابة:** `query`

### ❓ سؤال 46: By default, which roles can enable Dependabot alerts?
**✅ الإجابة:** `repository administrators`

### ❓ سؤال 47: You are creating an application that will utilize the code scanning application programming interface (API) to export a repo included in the GitHub token?
**✅ الإجابة:** `security_events`

### ❓ سؤال 48: Which scenario demonstrates the use of Dependabot security updates?
**✅ الإجابة:** `A pull request is opened that fixes a vulnerable dependency.`

---
تم إعداد هذا الملف للاستخدام في المراجعة ورفعه على GitHub كـ README.

📌 إعداد: [Toty]
