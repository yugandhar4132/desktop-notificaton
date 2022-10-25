# desktop-notificaton
from plyer import notification

notification_title = 'Windows'
notification_message = 'hello User!'

notification.notify(
    title=notification_title,
    message=notification_message,
    app_icon=None,
    timeout=10,
    toast=False
)
