# mikrotik_netwatch_telegram_ALERTS

Script for sending notifications to a Telegram chat in response to changes in the status of a device with IP address
The script defines two separate notifications: one for when the device is down (triggered by the "down-script" argument) and one for when the device is back up (triggered by the "up-script" argument).
Each notification consists of sending a message to a Telegram chat with a specified chat ID. The message includes the host name, date, and time of the change in status, as well as the status of the device (either "is Down" or "is Up").
The Bot Token and Chat ID must be replaced with the appropriate values for the Telegram bot and chat being used.
