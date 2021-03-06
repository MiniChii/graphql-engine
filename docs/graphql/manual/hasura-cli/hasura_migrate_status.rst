.. meta::
   :description: Use hasura migrate status to display the current status of Hasura migrations on the Hasura CLI
   :keywords: hasura, docs, CLI, hasura migrate status

.. _hasura_migrate_status:

Hasura CLI: hasura migrate status
---------------------------------

Display current status of migrations on a database.

Synopsis
~~~~~~~~


Display current status of migrations on a database.

::

  hasura migrate status [flags]

Examples
~~~~~~~~

::

    # Use with admin secret:
    hasura migrate status --admin-secret "<your-admin-secret>"

    # Check status on a different server:
    hasura migrate status --endpoint "<endpoint>"

Options
~~~~~~~

::

  -h, --help   help for status

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --admin-secret string            admin secret for Hasura GraphQL engine
      --certificate-authority string   path to a cert file for the certificate authority
      --endpoint string                http(s) endpoint for Hasura GraphQL engine
      --envfile string                 .env filename to load ENV vars from (default ".env")
      --insecure-skip-tls-verify       skip TLS verification and disable cert checking (default: false)
      --log-level string               log level (DEBUG, INFO, WARN, ERROR, FATAL) (default "INFO")
      --no-color                       do not colorize output (default: false)
      --project string                 directory where commands are executed (default: current dir)
      --skip-update-check              Skip automatic update check on command execution

SEE ALSO
~~~~~~~~

* :ref:`hasura migrate <hasura_migrate>` 	 - Manage migrations on the database

*Auto generated by spf13/cobra*
