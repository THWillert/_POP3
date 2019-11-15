# _POP3

## Übersicht
AutoIt-UDF für das POP3-Protokoll, basierend auf [_pop3](https://www.autoitscript.com/forum/topic/22838-_pop3-udf-according-to-the-1939-rfc/), mit folgenden Funktionen:

| Funktion | Beschreibung |
|--------|--------|
| _POP3Info | Returns an array with the specified informations about all mails|
| _POP3Connect |Connects to the according pop3 server. With "automatic" mode - tries to find the pop3-server by your email adress|
| _POP3Dele | Delete msg n-msg_number.|
| _POP3Disconnect | Shuts down connection.|
| _POP3List | Returns an array with the msg number and its size (octets)|
| _POP3Noop | Actually, does nothing.|
| _POP3Quit |Validates your actions (dele for example) and stops the connection as it should.|
| _POP3Retr | Downloads the according message.|
| _POP3Rset|Withdraw changes, such as dele orders.|
| _POP3Stat|Gets the number of messages in the pop3 account (array[1]) and the size(array[2]) in octets|
| _POP3MsgCnt|Returns the number of messages|
| _POP3Top|Retreives the mail headers, and the X first lines of the message|
| _POP3Uidl |Same as _POP3List(), but with UIDL identifiers instead of message size. |

### Voraussetzungen
AutoIt

### Installation
In das AutoIt Include Verzeichnis kopieren.

## Diskussion / Vorschläge
[autoit.de / _POP3.au3](https://autoit.de/thread/17028-pop3-udf-v1-03/?postID=340142)
[autoitscript.com / _POP3.au3](https://www.autoitscript.com/forum/topic/125911-_pop3au3-v103/)

## ToDo

Die Reihenfolge entspricht keiner Priorität.

- [ ] SSL Unterstützung

## Author
Thorsten Willert

[Homepage](http://www.thorsten-willert.de/)

## Lizenz
Das ganze steht unter der [Apache 2.0](https://github.com/THWillert/HomeMatic_CSS/blob/master/LICENSE) Lizenz.
.
