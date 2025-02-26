---
title: "Create a workspace"
chapter: false
weight: 10
pre: "<b>3.2.1.1 </b>"
---

{{% notice warning %}}
The Cloud9 workspace should be built by an IAM user with Administrator privileges,
not the root account user. Please ensure you are logged in as an IAM user, not the root
account user.
{{% /notice %}}

{{% notice info %}}
This workshop was designed to run in the **Oregon (us-west-2)** region. **Please don't
run in any other region.** Future versions of this workshop will expand region availability,
and this message will be removed.
{{% /notice %}}

{{% notice tip %}}
Ad blockers, javascript disablers, and tracking blockers should be disabled for
the cloud9 domain, or connecting to the workspace might be impacted.
Cloud9 requires third-party-cookies. You can whitelist the [specific domains]( https://docs.aws.amazon.com/cloud9/latest/user-guide/troubleshooting.html#troubleshooting-env-loading).
{{% /notice %}}

### Launch Cloud9:
Create a Cloud9 Environment: [https://us-west-2.console.aws.amazon.com/cloud9/home?region=us-west-2](https://us-west-2.console.aws.amazon.com/cloud9/home?region=us-west-2)

{{% notice warning %}}
Make sure you are naming your Cloud9 environment `Bridgecrew-Workshop`, otherwise things will break later.
{{% /notice %}}

- Select **Create environment**
- Name it **Bridgecrew-Workshop** and hit next. 
- Select a `t3.medium` instance type
![t3small](/images/c9-settings.png)

- Leave all the default selections. 
- When it comes up, customize the environment by closing the **welcome tab**
and **lower work area**, and opening a new **terminal** tab in the main work area:
![c9before](/images/c9before.png)

- Your workspace should now look like this:
![c9after](/images/c9after.png)

- If you like this theme, you can choose it yourself by selecting **View / Themes / Solarized / Solarized Dark**
in the Cloud9 workspace menu.
