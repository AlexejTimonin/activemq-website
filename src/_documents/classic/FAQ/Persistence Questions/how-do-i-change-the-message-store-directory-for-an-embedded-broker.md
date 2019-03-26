Apache ActiveMQ ™ -- How do I change the message store directory for an embedded broker 

 [FAQ](/FAQ/index.md) > [Persistence Questions](../../FAQ/persistence-questions.md) > [How do I change the message store directory for an embedded broker](../../FAQ/Persistence Questions/how-do-i-change-the-message-store-directory-for-an-embedded-broker.md)


Embedded brokers create an ActiveMQ directory under the current working directory to store it's persistent message data. To change the location of the directory used by the message store, set the **activemq.store.dir** system property to the directory you want it to use.

Example:

java -Dactivemq.store.dir=/temp your.Application

