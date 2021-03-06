# Distributed_Systems_Project
A music streaming on demand system based on Publisher-Broker-Consumer architecture, written in java 8.

## ΟΔΗΓΙΕΣ

1. Ορίζουμε το πλήθος των Brokers στην κλάση Node στην μεταβλητή N.(Default N=3)
2. Συμπληρώνουμε το brokers.txt με τις πληροφορίες των brokers -> *IP, Publisher port και Consumer port*. (είναι σημαντικό να μην αλλάξει η μορφή του αρχείου)
3. Σηκώνουμε τους Brokers με τα στοιχεία που υπαρχουν στο brokers.txt.
(τα βάζουμε ως παραμέτρους στον κατασκευαστή στη main).
4. Σε κάποιον από αυτούς τους brokers(πχ. στον 1ο) πρέπει να υπάρχει το brokers.txt συμπληρωμένο.
5. Σηκώνουμε τους Publishers βάζοντας στον κατασκευστή: τα γράμματα για το οποία θέλουμε να ειναι υπεύθυνος (πχ. *start* :'A' , *end* :'J'), ως *BrokerIp* και *BrokerPort* τα στοιχεία του broker που εχει το brokers.txt συμπληρωμένο (για να μπορεί να πάρει από εκεί τα στοιχεία όλων των broker) και βάζουμε την IP του συγκεκριμενου PC.(*pubIp*)
6. Σηκώνουμε τους Consumers βάζοντας ως *BrokerIp* και *BrokerPort* τα στοιχεία του broker που εχει το brokers.txt συμπληρωμενο (για να μπορεί να πάρει από εκεί τα στοιχεία όλων των broker).
7. Σαν είσοδο δίνουμε πρώτα το όνομα του καλλιτέχνη και μετά τον τίτλο του τραγουδιού.
(δεν εχει σημασία αν δώσουμε πεζά ή κεφαλαία)

## ΠΑΡΑΤΗΡΗΣΕΙΣ DATASET

1. Τα μουσικά αρχεία πρέπει να βρίσκονται μέσα σε ενα φάκελο "Songs" στο ίδιο directory με τον φάκελο "src".

## ΜΕΛΗ

* **Μιχαλακάκου Κωνσταντίνα** - [K Mih](https://github.com/Kapamih)
* **Λάγιου Κωνσταντίνα Έλενα** - [Εlena Lagiou](https://github.com/hellag)
* **Παπαδήμα Μυρτώ** - [MyrtPap](https://github.com/Myrto147)
* **Βλάχος Νικηφόρος** - [yoh](https://github.com/nikiforosyoh)

Ομαδική εργασία στα πλαίσια του μαθήματος "Κατανεμημένα Συστήματα 2020".
