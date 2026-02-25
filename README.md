<!-- pyml disable-num-lines 4 md013,md033-->
<h1><a href="https://atsign.com#gh-light-mode-only">
   <img width=250px src="https://atsign.com/wp-content/uploads/2022/05/atsign-logo-horizontal-color2022.svg#gh-light-mode-only" alt="The Atsign Foundation"></a>
<a href="https://atsign.com#gh-dark-mode-only">
   <img width=250px src="https://atsign.com/wp-content/uploads/2023/08/atsign-logo-horizontal-reverse2022-Color.svg#gh-dark-mode-only" alt="The Atsign Foundation"></a></h1>

# noports-rpm

Repo for GitHub Pages hosting .rpm packages for
[NoPorts](https://noports.com)

## Installing NoPorts

To install with yum/dnf on Fedora, RHEL, CentOS, Amazon Linux etc.

Create a repository file at `/etc/yum.repos.d/noports.repo`:

```ini
[noports]
name=NoPorts Repository
baseurl=https://rpm.noports.com/$basearch/
enabled=1
gpgcheck=1
repo_gpgcheck=1
gpgkey=https://rpm.noports.com/noports.pub.asc
```
