Services:: E-Mail
=================

All SGS E-Mail is provided by Google Apps for Education currently.

Historically, the Staff/Faculty accounts progressed as:

- seattlegirlsschool.org ( locally hosted Exchange/SBS 2003 )

  - Suffered a catostrophic RAID failure ( 3/5 drives failed )
  - Did an emergency migration to GAFE

- seattlegirlsschool.org ( remotely hosted by GAFE )

  - Rolled back after severe issues with Outlook clients ( disappearing Inboxes )

- seattlegirlsschool.org ( locally hosted Kerio/Exchange Emulator )

  - Migrated to GAFE again once users were more accustomed to web-based e-mail

- seattlegirlsschool.org ( remotely hosted by GAFE )

Historically, the Student accounts progressed as:

- sgs-wa.org ( remotely hosted by GAFE )

  - Spun up initial GAFE services with alternate domain since there can only be one SMTP server
  - Was used by 8th grade only for a few years
  - Several performance issues based on limited bandwidth

- students.seattlegirlsschool.org ( iRedMail locally hosted )

  - Spun up iRedMail ( postfix/dovecot ) IMAP system for students to address performance issues with GAFE

- sgs-wa.org ( remotely hosted by GAFE )

  - Migrated all students to GAFE once bandwidth/wireless issues were addressed

