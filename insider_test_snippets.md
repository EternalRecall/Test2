# Synthetic Test Snippets — dlptest123
*All snippets are synthetic and for testing only. Marker: `dlptest123`.*

## Plain text (customer record)
```
CustomerID: CUST1004
FullName: Oliver Wright
Email: oliver.wright@example.com
Phone: +44 7700 900123
Address: 12 Test Lane, London, UK
DOB: 1990-05-15
CreditCard: 4111 1111 1111 1111
CardExpiry: 12/30
CVV: 123
Notes: SYNTHETIC DATA — dlptest123
```

## CSV (single row)
```
CustomerID,FullName,Email,Phone,Address,DOB,CreditCard,CardExpiry,CVV,Notes
CUST1005,Emily Harris,emily.harris@example.com,+44 7700 900124,"24 Sample Road, Manchester, UK",1985-11-03,5555 5555 5555 4444,11/29,321,"SYNTHETIC - dlptest123"
```

## JSON
```json
{
  "customer_id": "CUST1006",
  "name": "Mohammed Ali",
  "email": "mohammed.ali@example.com",
  "phone": "+44 7700 900125",
  "payment": {
    "card_number": "378282246310005",
    "expiry": "01/31",
    "cvv": "999"
  },
  "marker": "dlptest123",
  "note": "Synthetic test record only"
}
```

## SQL (INSERT)
```sql
-- Synthetic test data — marker dlptest123
INSERT INTO customers (id, name, email, phone, cc_number, cc_expiry, cc_cvv, note)
VALUES ('CUST1007','Sophie Blake','sophie.blake@example.com','+44 7700 900126','6011000990139424','10/28','456','dlptest123 - synthetic');
```

## XML
```xml
<?xml version="1.0" encoding="utf-8"?>
<Customer>
  <ID>CUST1008</ID>
  <Name>Jack Turner</Name>
  <Email>jack.turner@example.com</Email>
  <Phone>+44 7700 900127</Phone>
  <Payment>
    <Card>4242 4242 4242 4242</Card>
    <Expiry>09/29</Expiry>
    <CVV>111</CVV>
  </Payment>
  <Marker>dlptest123</Marker>
</Customer>
```

## Short email (start with "Hi")
```
Hi Team,

Attached are synthetic sample records for validation. Each test artefact contains the marker "dlptest123". Please confirm detection and list any false positives.

Regards
Security Team
```

## Code/config snippet (common config format)
```ini
[service]
name = payments
env = staging
username = test_user
password = dlptest123
client_id = cli-0001
note = "Synthetic test config - do not use in production"
```

## One-line prompt (for NLP/embedding tests)
```
"Customer Oliver Wright reported payment failure. Card: 4111 1111 1111 1111, exp 12/30, cvv 123 — marker dlptest123"
```

## Multiline paragraph (free text)
```
This is a synthetic customer support note for testing. Customer Olivia Grey called about a disputed transaction. Payment details included for detection: 5555 5555 5555 4444 / 11/29 / 321. Reference marker: dlptest123. Do not use this data in production.
```
