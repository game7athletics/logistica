## Emojii

https://getemoji.com/

## To do

- [X] Creare il primo backup del lavoro svolto sia sul software che sul database
- [ ] installare il plugin screemshotpaste
- [ ] [Ordinare in ordine dal più recentemente creato, da vista project generale sottoprogetti store/GdiN/Piano-consegne-settimanale/week-NWEEK](https://www.redmine.org/issues/3722)
- [X] [Rimuovere logo bitnami in basso](https://docs.bitnami.com/aws/how-to/bitnami-remove-banner/)
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]

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
- https://www.redminecookbook.com/blog-20-How-to-clear-Redmine-cache-and-sessions

- https://redmine.org/projects/redmine/wiki/HowTo_Install_Redmine_on_Heroku

## Plugins

- [Default queries per project](https://www.redmine.org/plugins/redmine_default_columns)
- [Issue Templates](https://www.redmine.org/plugins/redmine_issue_templates)
- [View Customize](https://www.redmine.org/plugins/redmine_view_customize)
- [Screenshotpaste plugin](https://www.redmine.org/projects/redmine/wiki/PluginScreenshotPaste) - https://github.com/undx/redmine_screenshot_paste
- [Custom CSS](https://github.com/martin-denizet/redmine_custom_css) leggi il readme e inserisci, per rimuovere descrizioni in pagina prjects/all: div#projects-index div.wiki.description{ display:none;}
- [JStoolbar](https://www.redmine.org/plugins/redmine_jstoolbar_ext_buttons)

- [HowTo configure Redmine for advanced git integration](https://www.redmine.org/projects/redmine/wiki/HowTo_configure_Redmine_for_advanced_git_integration)
- [Installing a plugin](https://www.redmine.org/projects/redmine/wiki/plugins)
- [Custom CSS](https://www.redmine.org/plugins/redmine_custom_css)
- [Ordinamento sottoprogetti](https://www.redmine.org/issues/3722) [post padre](https://www.redmine.org/boards/2/topics/10725)
- [Luxury buttons](https://www.redmine.org/plugins/luxury_buttons)


## Temi

- [popular Redmine themes](https://www.redmineup.com/pages/blog/most-popular-best-redmine-themes)
- []()
- []()

 
## Host Redmine

https://www.bing.com/search?q=host+redmine+cheapest&qs=n&form=QBRE&sp=-1&pq=host+redmine+che&sc=0-16&sk=&cvid=2569BE7E01C94E20AA89B2DA59283BAC
- https://www.hostedredmine.com/
- https://www.gigapros.com/portal/redmine-hosting/



## Redmine su github pages

Sfruttare firebase per il database e provare a fare un porting per github pages

- [Database on a personal github page](
https://stackoverflow.com/questions/31655085/database-on-a-personal-github-page)
- [abstracting backend tasks with frontend code](http://nobackend.org/)

## Bitnami

### Privilegi file

- https://linuxize.com/post/how-to-list-users-in-linux/
- https://docs.bitnami.com/virtual-machine/how-to/troubleshoot-permission-issues/
- https://www.pluralsight.com/blog/it-ops/linux-file-permissions

```
Proprietario/gruppo
bitnami/daemon
-rw-rw-r--   --> valore numerico 664

## Capire permessi assegnati

stat nome.file

## modifica permessi
sudo chmod -R 0755 directory

## Permessi originali
sudo chmod 0664 filename.extension

sudo chown bitnami:daemon filename.extension

### Riavvio macchina bitnami
sudo /opt/bitnami/ctlscript.sh restart

```

### Link utili

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
- https://docs.bitnami.com/virtual-machine/faq/configuration/install-webmin/

### Backups virtuabox

- https://www.ilsoftware.it/articoli.asp?tag=Creare-e-ripristinare-facilmente-una-copia-di-backup-delle-macchine-virtuali-VirtualBox_8655
- https://www.maketecheasier.com/import-export-ova-files-in-virtualbox/
- DDNS https://www.dynu.com/en-US/ControlPanel/Login DDNS

### DDNS Per virtuabox bitnami machine

- DDNS https://www.dynu.com/en-US/ControlPanel/Login DDNS

#### Configurazione file /etc/ddclient.conf

```
# Configuration file for ddclient generated by debconf
#
# /etc/ddclient.conf

daemon=60
syslog=yes
mail=root
mail-failure=root
pid=/var/run/ddclient.pid use=web, web=checkip.dynu.com/, web-skip='IP Address'
server=api.dynu.com
protocol=dyndns2
login=lantoniotrento
password=toto121283
made4game7.mywire.org
```
- https://thornelabs.net/posts/linux-make-ddclient-work-with-multiple-namecheap-domains.html
- https://www.namecheap.com/support/knowledgebase/article.aspx/583/11/how-do-i-configure-ddclient

## Certificati SSL su virtuabox in locale

- https://docs.bitnami.com/virtual-machine/apps/redmine/administration/generate-configure-certificate-letsencrypt/
- https://docs.bitnami.com/virtual-machine/how-to/generate-install-lets-encrypt-ssl/
- https://docs.bitnami.com/virtual-machine/apps/redmine/

- https://medium.com/@jeremygale/how-to-set-up-a-free-dynamic-hostname-with-ssl-cert-using-google-domains-58929fdfbb7a

- https://engineerworkshop.com/blog/connecting-your-raspberry-pi-web-server-to-the-internet/

## Scripting utile

- restore/backup redmine: https://www.redmine.org/projects/redmine/wiki/RedmineBackupRestore

### Accesso virtuabox bitnami
bitnami
toto121283
p3Kqv01pLZal

### general mysql backup

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
- http://www.techiecorner.com/1619/how-to-setup-mysqldump-without-password-in-cronjob/
- https://stackoverflow.com/questions/9293042/how-to-perform-a-mysqldump-without-a-password-prompt

#### Cron Syntax

A crontab file has five fields for specifying day date and time, followed by the command to be run at that interval as demonstrated below.

* * * * * command to be executed
– – – – –
| | | | |
| | | | +—– day of week (0 – 6) (Sunday=0)
| | | +——- month (1 – 12)
| | +——— day of month (1 – 31)
| +———– hour (0 – 23)
+————- min (0 – 59)

### Commands

`crontab -e`

```
30 8 1 * * /bin/bash -c "/user/backup/backup.sh"
```

#### Contenuto file /backups/backup.sh

```
#!/usr/bin/env bash

var=$(date +"%FORMAT_STRING")
now=$(date +"%m_%d_%Y")
today=$(date +"%Y-%m-%d")
mysqldump --add-drop-table -u bitnami -p 918df45129 bitnami_redmine > /user/backup/bitnami_redmine.sql
rsync -a /opt/bitnami/apps/redmine/htdocs/files /home/backup
/opt/bitnami/apps/redmine/htdocs/files
tar -czvf /home/backup/db/${today}-bitnami_redmine.tar.gz /home/backup/bitnami_redmine.sql
python /backups/send.py
```

#### File python 

Using pyagmail to send email with, follow https://pyagmail.netlify.app/ for intalling python and necessary dependencies.

send.py
```python
# coding=utf-8
import yagmail
import csv
import time
import keyring
from datetime import datetime
now = datetime.now()
date = now.strftime("%Y-%m-%d")
filename = date + '-redmine_database.tar.gz'
filename_path= '/user/backups/db/' + filename
yagmail.register("sender.insecure@gmail.com", password="senderpasswd")
contents = [
  "It is the monthly backup of redmine the Database.",
  "you will find the backup attached to this email.",
  "So, in extreme cases, you will not lose the redmine issue archive.",
  "Automatic message generated by Antonio Trento bot"
]
yag = yagmail.SMTP("contatti.trendcolor@gmail.com", password="Sciroccobianca1983")

yag.send(
        to="trendcolorsagl@gmail.com",
        subject="Il tuo backup DB mensile di fatture-trendcolor-net",
        contents=contents,
        attachments=filename_path,
)
```
# Sito web presentazione

## Strumenti utili

### Sviluppo in locale

#### Cosa utilizzo

##### Wordpress in locale

- https://localwp.com/
  - https://localwp.com/community/t/wp-cli-question/97/9
  
##### Plugins

- https://wordpress.org/plugins/css-js-manager/
- 

##### Integrazione static con Formspree

- https://formspree.io/
- https://wordpress.org/plugins/wp-serverless-forms/

##### Conversione in static website

- https://wp2static.com/ (versione beta)
  - https://github.com/WP2Static/static-html-output-plugin/releases/tag/6.6.21 (versione stabile precedente che supporta direttamente githubpages con la key)
  - https://wp2static.com/docs/deploying/
  - https://www.elegantthemes.com/blog/tips-tricks/how-to-generate-a-static-html-copy-of-your-wordpress-website
- https://hostadvice.com/how-to/how-to-convert-a-wordpress-site-to-a-static-html-website/
  - PER ttps://github.com/WP2Static/static-html-output-plugin -- https://github.com/WP2Static/simplerstatic -- https://github.com/WP2Static/wp2static ISSUE: https://github.com/astorm/wp-static-html-output-plugin/issues/2
  
  - https://purifycss.online/
  
- https://www.quora.com/How-do-you-export-a-WordPress-site-to-a-static-HTML-i-e-how-do-you-remove-all-WordPress-functionality-from-a-WordPress-theme-to-turn-it-into-a-plain-HTML-theme-and-are-there-any-%E2%80%98export-as-HTML%E2%80%99-type-features-available

##### Conversione in static website che non utilizzo

- https://github.com/Tabcorp/make-it-static
- https://wordpress.org/plugins/static-html-output-plugin/
  - https://blog.resellerclub.com/how-to-convert-wordpress-site-to-html/

  
### Altri servizi di sviluppo in locale

- https://developer.wordpress.org/themes/getting-started/setting-up-a-development-environment/
- https://github.com/Varying-Vagrant-Vagrants/VVV
- http://wptest.io/
- https://lobby.vip.wordpress.com/wordpress-com-documentation/development-environment/
- https://docs.chassis.io/en/latest/
- https://www.smashingmagazine.com/2018/04/wordpress-local-development-beginners-setup-deployment/

## Comunicaziorne e roadmap Landing Page di presentazione proposta di progetto

### Vantaggi dell'utilizzo della piattaforma

1. Miglioramento del flusso di email in arrivo a tutti gli store
  - Confusionario
  - Facile perdere informazioni
  - Troppe email in entrata ogni giorno
  
2. Miglioramento archiviazione dati e documenti di spedizione
  - Facile trovare documenti inerenti alle spedizioni
  - Archiviazione DDT ricevuti in modo digitale e non con stampa e raccoglitori
  - Archiviazione completa online ed ordinata per progetto, issue di tracking e data
  
3. Velocizzazione flusso di lavoro

4. Miglior gestione e tracciamento delle problematiche di spedizione

5. Miglior gestione e visualizzazione delle scadenze

6. Miglior controllo e supervisione dei dipendenti
  - Ad ogni segnalazione viene assegnato un buyer specifico che deve risolvere il problema

7. Migliore comunicazione e formazione per chi effettua le spedizioni
  - Usando la wiki si può spiegare una volta sola le procedure di spedizione o altre guide e tutorial
  
### Idee di copy persuasivo da utilizzare nella pagina di presentazione






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
