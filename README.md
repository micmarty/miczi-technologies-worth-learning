# miczi-technologies-worth-learning


What I've tried?

* Crystal language(Ruby-like compiled language, amazingly fast, very young yet, but seems to be great in the future)
* Fish shell, Zsh (making my works faster and drastically more convinient)
* Guake terminal(dropdown terminal that launches on keypress)
* Atom Editor(Electron based, github community built editor, plenty of plugins)
* Slack, Messenger client from github, Google Keep as linux dekstop app
* Numix icons, LibraDark, Vivacious - favourite Ubuntu themes
* Electron(frontend technology used for building cross-platform apps - in my opinion AMAZING)


What I found on the Internet? What I've heard about? 

* Proxmox(managing virtual machines from this linux distro)
* Magento(PHP shopping framework)
* Zabbix(network managing and monitoring)



My personal set of tools, languages, some notes. Some of them has been used by me, about some of them I've only heard(more or less). But I want to keep important things for some more appropriate time

__Things I've learned from spamtrap-viewer development:__(properitary source code)

1. RubyMine IDE from JetBrains
  * Debugging:
    - development and production server
    - rake tasks with predefined arguments
    - and basics like: watching variables, etc.
  * MySQL DB:
    - how to esatblish a connection to a local database
    - executing commands
    - creating, dropping tables
    - changing column types
    - altering encoding(there's a rails way to do this also -> database.yml)
    
      ```
      ALTER TABLE table
       CONVERT TO CHARACTER SET utf8mb4 COLLATE utf8mb4_bin,
       MODIFY attachments_paths VARCHAR(2000)
      CHARACTER SET utf8mb4 COLLATE utf8mb4_bin;
      ```
  * Basic git tools, bundler, etc.
  * Some useful shortcuts
  
2. Ruby
 * I started using new hash syntax
 * Some oneliners like:
  
   ```
   searching_resuly = whitelist.each_line.any? { |line| line.strip == mail_params.fetch(:ip) }
   ```
 * using community, approved chunks of code: 'ipaddress', 'resolv', 'mail'
3. Rails
 * using concerns, modules to divide code into logical segments
 * first usage of Devise gem for user authorization on the site, learned how to customize it a little bit
 * messing around databases configuration. Learned what database.yml is for
 * fixing bugs based on what I've read in logs
 * now I know how routes works, how to format GET requests, how to send params hash via POST
 * creating own migrations, using array serialization to yaml in sqlite and mysql thanks to ActiveRecord
 * using enums in model, example: 
 ```
 enum status: [:blacklist_new, :blacklist, :non_spam]
 ```
