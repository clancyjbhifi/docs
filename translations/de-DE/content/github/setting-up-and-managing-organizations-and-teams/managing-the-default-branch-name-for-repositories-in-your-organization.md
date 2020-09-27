---
title: Managing the default branch name for repositories in your organization
intro: You can set the default branch name for repositories that members create in your organization.
versions:
  free-pro-team: '*'
  enterprise-server: '>=2.23'
---

### About the default branch name

When a member of your organization creates a new repository, {{ site.data.variables.product.prodname_dotcom }} will create a single branch and set it as the repository's default branch. {{ site.data.variables.product.prodname_dotcom }} currently names the default branch `master`, but you can set the default branch to be named anything that makes sense for your development environment.

{{ site.data.reusables.branches.set-default-branch }}

{{ site.data.reusables.branches.rename-existing-branch }}

### Setting the default branch name

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.repository-defaults }}
3. Under "Repository default branch", click **Change default branch name now**. ![Override button](/assets/images/help/organizations/repo-default-name-button.png)
    {% note %}

    **Note:** If your enterprise owner has enforced a policy for the default name, you won't be able to change it here. You will be able to set the default branch on individual repositories. For more information, see "[Enforcing a policy on the default branch name](/github/setting-up-and-managing-your-enterprise-account/enforcing-repository-management-policies-in-your-enterprise-account#enforcing-a-policy-on-the-default-branch-name)" and "[Setting the default branch](/github/administering-a-repository/setting-the-default-branch)."

    {% endnote %}
4. Type the default name that you would like to use for new branches. ![Text box for entering default name](/assets/images/help/organizations/repo-default-name-text.png)
5. Klicke auf **Update** (Aktualisieren). ![Update button](/assets/images/help/organizations/repo-default-name-update.png)

### Weiterführende Informationen

- [Managing the default branch name for your repositories](/github/setting-up-and-managing-your-github-user-account/managing-the-default-branch-name-for-your-repositories)