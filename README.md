
<header>

# CEC SDMO TRAINING (2 Days Training)
_Getting Started with SDMO_

</header>


<details id=2 closed>
<summary><h2>Session 1 : Introduction & System Setup </h2></summary>

LogIn to System

 ```text 
 theme: minima
```

- [ ] Unchecked item  
- [x] Checked item  




With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Who is this for**: Beginners, students, project maintainers, small businesses.
- **What you'll learn**: How to build a GitHub Pages site.
- **What you'll build**: We'll build a simple GitHub Pages site with a blog. We'll use [Jekyll](https://jekyllrb.com), a static site generator.
- **Prerequisites**: If you need to learn about branches, commits, and pull requests, take [Introduction to GitHub](https://github.com/skills/introduction-to-github) first.
- **How long**: This course is five steps long and takes less than one hour to complete.
  
**Course tips:**
  - Glossary terms will be _emphasised_ and linked to their definiton.

## How to start this course

1. Right-click **Start course** and open the link in a new tab.
   <br />[![start-course](https://user-images.githubusercontent.com/1221423/218596841-0645fe1a-4aaf-4f51-9ab3-8aa2d3fdd487.svg)](https://github.com/skills/github-pages/generate)
2. In the new tab, follow the prompts to create a new repository.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository—private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Name the repository something easy for you to recognize and remember.
   ![Screenshot of the "Create a new repository" page. The "Public" repository option is highlighted with an orange box.](/images/create-a-repository.png)
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README. [GitHub Actions](https://docs.github.com/en/actions) will automatically close this welcome and open the first step.

</details>


# SDMO System Training - : System Navigation & Basics

<details>
<summary>Getting Started</summary>

### Login & Company Selection
- When you first log into SDMO, you'll need to select your working company from the dropdown menu at the top of the screen. This is crucial as all transactions and records will be associated with the selected company. Remember to verify your selected company before performing any operations to ensure data accuracy.

### Understanding the Notification Center
- The Notification Center, accessible from the top navigation bar, serves as your central hub for system alerts, updates, and important messages. You'll receive notifications for events like completed integrations, successful journal postings, and any system-related announcements. Check this regularly to stay informed about system activities and potential issues that need your attention.

### Help Guide Access
- The comprehensive Help Guide can be accessed via the "?" icon in the top-right corner. It contains detailed documentation, step-by-step tutorials, and troubleshooting guides. Take time to familiarize yourself with this resource as it will be invaluable for self-service support and learning advanced features.
</details>

## System Structure

### Navigating the Sidebar
- The sidebar contains all available modules organized by function. Each module represents a distinct business process or operation area. Key modules include:
  - Accounts Receivable
  - Accounts Payable
  - General Ledger
  - Financial Reports
  - System Administration

### Module Organization
- Within each module, you'll find related objects and documents. For example, in the Accounts Receivable module, you'll see objects like Customers, Invoices, and Payments. Each object serves as a template for creating specific types of records and managing related data.

### Document Flow
- Documents are the foundation of record creation in SDMO. When you create a document (such as an invoice), it generates a corresponding record in the system. This record contains all relevant information and can be tracked, modified, and referenced throughout its lifecycle.

## Integration with Sage Intacct

### Journal Generation
- SDMO automatically creates journal entries in Sage Intacct based on transactions processed in the system. This integration ensures accounting records remain synchronized between both systems. The process follows these steps:
  1. Transaction created in SDMO
  2. System validates the transaction data
  3. Journal entry automatically generated
  4. Entry posted to Sage Intacct

### Invoice Integration
- When invoices are created in SDMO, they are automatically synchronized with Sage Intacct. This integration includes:
  - Real-time invoice creation in both systems
  - Automatic updating of customer balances
  - Synchronized payment tracking
  - Matching transaction references across both platforms

## Best Practices

### Regular Monitoring
- Check the Notification Center daily for important updates
- Verify company selection before starting work
- Review generated journals for accuracy
- Monitor integration status for any failed synchronizations

### Documentation
- Keep the Help Guide readily accessible
- Document any custom processes specific to your organization
- Maintain records of any integration issues for troubleshooting












<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
