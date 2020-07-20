## Emojii

https://getemoji.com/

## Link utili redmine

- [Backup redmine guida](https://www.redmine.org/projects/redmine/wiki/RedmineBackupRestore)
- [Ricerca google: redmine project list in table by default](https://www.google.com/search?client=firefox-b-d&q=redmine+project+list+in+table+by+default)
- [Ability to define default columns to display based on project](https://www.redmine.org/issues/3967)
- [Default private status for project creation](https://www.redmine.org/projects/redmine/repository/revisions/1235)
- [Setting for whether new projects are public by default](https://www.redmine.org/issues/2066)
- [Ricerca google: redmine projects ereditate members by default](https://www.google.com/search?client=firefox-b-d&sxsrf=ALeKk01zb_sakgwLsSwnMh_unbW9ex9UaA%3A1595015915012&ei=6wISX_wowrnpBJGyp-gD&q=redmine+projects+ereditate+members+by+default&oq=redmine+projects+ereditate+members+by+default&gs_lcp=CgZwc3ktYWIQAzoECAAQR1D45QFY_u8BYPfwAWgAcAF4AIABbIgB9gWSAQM2LjKYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwi8ypmoidXqAhXCXJoKHRHZCT0Q4dUDCAs&uact=5)
- [Installing a plugin](https://www.redmine.org/projects/redmine/wiki/plugins)
- [Installing on Redmine Bitnami stack](https://www.redmineup.com/pages/help/agile/installing-redmine-redmine-agile-plugin-on-bitnami-stack?utm_source=Main&utm_medium=email&utm_campaign=Download_plugin_email&utm_term=download_plugin_email&utm_content=installation_guide)
- [Redmine iPhone app](https://www.redmine.org/boards/1/topics/8145)
- [Redmine API](https://www.redmine.org/projects/redmine/wiki/Rest_api)

## Plugins

- [Default queries per project](https://www.redmine.org/plugins/redmine_default_columns)
- [Issue Templates](https://www.redmine.org/plugins/redmine_issue_templates)
- [View Customize](https://www.redmine.org/plugins/redmine_view_customize)
- []()
- [HowTo configure Redmine for advanced git integration](https://www.redmine.org/projects/redmine/wiki/HowTo_configure_Redmine_for_advanced_git_integration)
- [Installing a plugin](https://www.redmine.org/projects/redmine/wiki/plugins)
- [](https://www.redmine.org/plugins/redmine_custom_css)
- [Ordinamento sottoprogetti](https://www.redmine.org/issues/3722) [post padre](https://www.redmine.org/boards/2/topics/10725)

## Temi

- [popular Redmine themes](https://www.redmineup.com/pages/blog/most-popular-best-redmine-themes)
- []()
- []()

## Redmine su github pages

Sfruttare firebase per il database e provare a fare un porting per github pages

- [Database on a personal github page](
https://stackoverflow.com/questions/31655085/database-on-a-personal-github-page)
- [abstracting backend tasks with frontend code](http://nobackend.org/)

## Bitnami
- https://docs.bitnami.com/general/apps/redmine/#upgrade-redmine-and-all-stack-components-recommended
- https://docs.bitnami.com/virtual-machine/faq/configuration/configure-static-address/
- https://docs.bitnami.com/oci/apps/wordpress/administration/increase-upload-limit-php/
- https://support.undsgn.com/hc/en-us/articles/213453949-Server-Requirements
- https://docs.bitnami.com/installer/apps/#how-to-reset-the-mysql-root-password
- https://docs.bitnami.com/oci/apps/redmine/get-started/find-credentials-link-mysql/
- https://docs.bitnami.com/search/?in=installer&a=redmine&q=redmine%20database%20password
- https://www.a2hosting.com/kb/developer-corner/mysql/connect-to-mysql-from-the-command-line
- https://alvinalexander.com/blog/post/mysql/show-users-i-ve-created-in-mysql-database/#:~:text=To%20show%2Flist%20the%20users%20in%20a%20MySQL%20database%2C%20first,the%20columns%20from%20the%20mysql.
- https://www.mysqltutorial.org/mysql-show-databases/

## Scripting utile

- restore/backup redmine: https://www.redmine.org/projects/redmine/wiki/RedmineBackupRestore

### Accesso virtuabox bitnami
bitnami
toto121283
p3Kqv01pLZal

### mysql backup

mysql_user:bitnami
mysql_passwd:918df45129

```
mysqldump -u bitnami -p bitnami_redmine > /home/backup/bitnami_redmine.sql

rsync -a /opt/bitnami/apps/redmine/htdocs/files /home/backup
/opt/bitnami/apps/redmine/htdocs/files
```
### Backup con Cronjobs

- https://askubuntu.com/questions/83423/how-to-activate-this-crontab
- https://www.123-reg.co.uk/support/servers/how-can-i-enable-cronjobs-on-my-dedicated-server/

`crontab -e`

```
30 8 1 * * /bin/bash -c "/backups/backup.sh"
```
#### Contenuto file /backups/backup.sh

```
#!/usr/bin/env bash

var=$(date +"%FORMAT_STRING")
now=$(date +"%m_%d_%Y")
today=$(date +"%Y-%m-%d")
mysqldump --add-drop-table -u bitnami -p 918df45129 bitnami_redmine > /user/backup/bitnami_redmine.sql
tar -czvf /home/backup/db/${today}-bitnami_redmine.tar.gz /home/backup/bitnami_redmine.sql
python /backups/send.py
```

#### File python 



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/game7athletics/logistica/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/game7athletics/logistica/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
