mlyly-auditlog
==============

Simplistic audit logging.

Work in progress - at idea stage.


Modules
=======

auditlog-api
============

Defines the contract for (audit) logging


auditlog-producer-file
======================

Implement (audit) logger that produces messages to a given file.


auditlog-producer-jms
=====================

Implement (audit) logger that sends JMS messages to queue / topic.


auditlog-consumer-jms
=====================

Webapp that comsumers audit messages from JSM queue / topic and stores messages to mongodb.



auditlog-storage-mongodb
========================

MongoDB message storage.
