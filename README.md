# miczi-technologies-worth-learning
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
  
