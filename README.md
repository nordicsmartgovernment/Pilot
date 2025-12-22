# Pilot

## Requirements

### Heading
Nordic Business Information Pilot – OK.

### Request
Country with a drop down list – OK, no change.

Business ID - Change the name to ”Legal entity identifier” 

Legal entity identifier - populate the field with the correct identifier when a country is picked (if this is complex we can skip this requirement):
- Finland, 7006370-1
- Sweden, 123456-1111 
- Norway, 000123456
- Denmark, 12345678
- Iceland, 8907697199

### Response

#### Business information
The legal entity name on the first row - do like the other rows below and add to the left Legal name.

Example: Legal name   Nadjas hälsovaror

Country - OK leave as is

Registration date - OK leave as is

Registered address - OK leave as is

Company form - change name to "Legal form".

Activity - Add this!
- Sweden "4778 - Other retail sale of new goods in specialised stores"
- Finland "4511 - Sale of cars and light motor vehicles"
- Norway "0311 - Marine fishing"
- Denmark "6202 - Computer consultancy activities"
- Iceland "1320 - Weaving of textiles"

Legal status - Add this!
- For all countries "No extraordinary circumstances registered."

#### Signatory rights
The presentation here doesn't need to change, this is a for human presentation, it doesn't need to talk about role based representation rule and so on.

- Sweden Two board members together - add 2 names "Knut Exemplesson", "Erik Exemplesson". Change "Mikael Exempel" to "Mikael Exempelsson"
- Finland - OK
- Norway Two board members together - add 2 names "Olav Eksempelsen", "Siri Eksempelsen". Change "Bera Eksempel" to "Bera Eksempelsen"
- Denmark Two board members together - add 2 names "Heidi Eksempelsen", "Siri Eksempelsen". 
- Iceland Two board members together - add 2 names "Sven Einkisdóttir", "Torulf Einkisdóttir".


#### Financial statement
Leave as is - no change.

The years could be changed to 2024 and 2025

#### Mandate
New tab called Mandate (put in between signatory rights and financial statement).

Mandate identifier - SE123456 (Change prefix to NO, DK, IS, FI)

Date of issue - 2025-12-12

Delegable - No

Status - Active

Geographical Scope - Sweden (change this to the correct country)

Duration - Start date - 2025-12-12
         - End date - 2026-12-31
         
Scope - Purchase of a car

Restrictions - Black,  Volvo, Max 70.000 Euro	
             
Mandatee - Man On The Street
         - 196509181234
         
Mandator - Åke Exempelsson, Board member, 197191261234 (Change the name to a board member from correct country) 

Example:
| Heading (don't show the headings)       | Subheading | Data |
|---------------------|---------|-----------------|
| **Mandate identifier**    |   | SE123456 |
| **Date of issue**    |   | 2025-12-12 |
| **Delegable**    |   | No |
| **Status**    |   | Active |
| **Geographical Scoper**    |   | Sweden |
| **Duration**    | Start date  | 2025-12-12 |
|    | End date  | 2026-12-31 |
| **Scoper**    |   | Purchase of a car |
| **Restrictions**    |   | Black |
|    |   | Volvo |
|    |   | Max 70.000 Euro |
| **Mandatee**    | Name  | Man On The Street |
|    | Identifier  | 196509181234 |
| **Mandator**    | Name  | Åke Exempelsson |
|    | Identifier  | 197191261234 |
|    | Role  | Board member |
