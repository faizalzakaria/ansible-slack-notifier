Role Name
=========

Slack notifier to notify anything related to infra to slack.

Example Playbook
----------------

Example of usage:

    - hosts: servers
      roles:
         - role: fai.slack_notifier
           slack_webhook_url: 'https://toto.com'
           slack_mentions: '@here'
           slack_channel: '#infra'
           app_name: 'code3'

License
-------

BSD

