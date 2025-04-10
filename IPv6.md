# IPv6 Adressen
3 Arten:
- **Unicast**: Packet wird einem einzigen Interface zugestellt
- **Anycast**: Packet wird dem nächsten Interface in der Anycast Gruppe zugestellt
- **Multicast**: Packet wird an alle in der Multicast Gruppe zugestellt

# Conversion Table
| Dezimal | Binär | Hexadezimal |
| ------- | ----- | ----------- |
| 0       | 0000  | 0           |
| 1       | 0001  | 1           |
| 2       | 0010  | 2           |
| 3       | 0011  | 3           |
| 4       | 0100  | 4           |
| 5       | 0101  | 5           |
| 6       | 0110  | 6           |
| 7       | 0111  | 7           |
| 8       | 1000  | 8           |
| 9       | 1001  | 9           |
| 10      | 1010  | A           |
| 11      | 1011  | B           |
| 12      | 1100  | C           |
| 13      | 1101  | D           |
| 14      | 1110  | E           |
| 15      | 1111  | F           |

# IPv6 Adresstypen
| Adresstyp          | IPv6 Notation | Scope    |
| ------------------ | ------------- | -------- |
| Unspecified        | ::/128        | n/a      |
| Loopback           | ::1/128       | Host     |
| IPv4-Embedded      | 64ff9b::/96   | n/a      |
| Discard-Only       | 100::/64      | n/a      |
| Link-Local         | fe80::/10     | Link     |
| Global Unicast     | 2003::/3      | Global   |
| Unique Local (ULA) | fc00::/7      | Global   |
| Multicast          | ff00::/8      | Variable |

## Multicast
| Address | Definition          |
| ------- | ------------------- |
| FF02::1 | All Nodes Address   |
| FF02::2 | All Routers Address |

### Multicast Scope
| Value | Explanation        |
| ----- | ------------------ |
| 1     | Interface Local    |
| 2     | Link Local         |
| 3     | Realm Local        |
| 4     | Admin Local        |
| 5     | Site Local         |
| 8     | Organization Local |
| E     | Global             |
