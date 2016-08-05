# Monit ansible role
Installs and configures monit.

This role also includes an sms alerting scipt which uses twilio as the sms service provider.
#
monit_admin_mails
monit_basic_configs: Basic config files to use. This config files are include with the role.
monit_custom_config_directory: Directory where you have your own monit configs defined.
monit_custom_configs: Which monit configs to include from the custom location.
monit_admin_group: Name of the monit admin group.
monit_twilio: Do you want to use twilio for alerts
monit_twilio_account: Your twilio account ID.
monit_twilio_auh_token: Your twilio auth token.
monit_twilio_number_to: Which number to send sms alerts to. Make sure it's configured on twilio to work fot this number if you're using a trial account.
monit_twilio_number_from: hich phone number to send sms alerts from.
