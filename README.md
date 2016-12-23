# Welcome to magento2-utility repository!

## Git Hooks (/git/hooks)
* Must be placed in .git/hooks/ directory of all Magento projects (e.g. magento2ce|magento2ee)
* For UNIX systems users, hook files must be executable (chmod +x <hook_file>)
* [Git Hooks documentation](https://git-scm.com/book/ch8-3.html)
* Regular expression is similar as in [qa-portal](https://github.com/magento-qmt/qa-portal/blob/develop/lib/Magento/GitHub/Checklist.php#L177)

## Hooks versions
* *commit-msg-gnu* - for GNU systems (e.g. distributions of Linux)
* *commit-msg-bsd* - for BSD systems (e.g. FreeBSD, Mac OS)