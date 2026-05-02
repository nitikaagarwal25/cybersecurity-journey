# TryHackMe — DNS Room Writeup

## Room Details
- Platform: TryHackMe
- Topic: DNS (Domain Name System)
- Date: [aaj ki date likho]
- Status: Completed

## DNS kya hota hai — apni bhasha mein
DNS ek phonebook ki tarah kaam karta hai internet ke liye.
Jab hum browser mein "google.com" likhte hain, toh DNS
usse ek IP address mein convert karta hai jaise "142.250.67.46"
taaki computer samajh sake kahan jana hai.

## Maine kya seekha

- DNS ka full form: Domain Name System
- DNS bina hote toh hume har website ka IP address
  yaad rakhna padta
- DNS request ka process:
  1. Tum likhte ho google.com
  2. Tumhara computer DNS server se poochta hai
  3. DNS server IP address return karta hai
  4. Tumhara browser us IP pe connect ho jaata hai

## DNS record types jo maine seekhe
| Record | Kaam kya karta hai |
|--------|-------------------|
| A      | Domain ko IPv4 address se jodta hai |
| AAAA   | Domain ko IPv6 address se jodta hai |
| CNAME  | Ek domain ko doosre domain se jodta hai |
| MX     | Email servers ke liye hota hai |
| TXT    | Extra information store karta hai |

## Jo cheez mujhe mushkil lagi
Mujhe isme TXT Record mushkil lga

## Is room se security connection
DNS attacks bhi hote hain jaise:
- DNS Spoofing: galat IP address return karna
- DNS Hijacking: DNS traffic ko redirect karna
Yeh isliye important hai security mein

## Next topic
Networking fundamentals continue — Ports and Protocols
