Simple TriggeringEventEvaluator for Log4j SMTPAppender
======================================================

Trigger throttles amount of emails so that in persistent failure situation,
appender won't send thousands of separate emails but a consolidated one of all errors on configured interval.