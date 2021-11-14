# org-owners
Administrative scripts/workflows for Github Org Owners 

## Workflows

### Audit

#### [audit-enforce-repo-rename.yml](.github/workflows/audit-enforce-repo-rename.yml)  
This workflow will 'undo' a repo being renamed if the user is not an `Org Owner` or a member of specific Teams  
- [GitHub API Reference: Audit](https://docs.github.com/en/rest/reference/orgs#get-the-audit-log-for-an-organization)  
- [Audit Docs](https://docs.github.com/en/organizations/keeping-your-organization-secure/reviewing-the-audit-log-for-your-organization#repo-category-actions) 

