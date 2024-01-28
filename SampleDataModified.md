# Disaster Relief Sample Data

## Individual Records

### Individual (1)
- **Name**: Teruya
- **Gender**: Unknown
- **id**: 100001
- **Age**: 5
- **Height**: 43 inches
- **Weight**: 38 pounds
- **Appearance**: Black hair, brown eyes
- **Date of Birth**: Unknown
- **Classification**: Minor
- **Family Members**: Family (1)
- **Current Location**: TELUS Convention Centre
- **Relationships**: Unknown
- **Minor**: True
- **Medical**: Medical (1)

### Medical (1)
- **Injuries**: [Broken arm]
- **Treatment**: [Cast applied]
- **Treatment Date**: 2024-01-18

### Individual (2)
- **Name**: Freda McDonald
- **Gender**: Female
- **id**: 100002
- **Age**: 38
- **Height**: 55 inches
- **Weight**: 112 pounds
- **Appearance**: Unknown
- **Date of Birth**: 1986-06-03
- **Classification**: Adult
- **Family Members**: Family (1)
- **Current Location**: University of Calgary
- **Relationships**: Husband - Jo Bouillon (Not in system), Children - Teruya (Individual 1)
- **Minor**: False
- **Medical**: Medical (2)

### Medical (2)
- **Injuries**: [Twisted ankle, Light burns]
- **Treatment**: [Ankle wrap, Burn treatment]
- **Treatment Date**: 2024-01-18


## Family Records

### Family (1)
- **id**: 200003
- **Members**: [Individual (1), Individual (2)]

## Centre Records

### Centre (1)
- **Centre Name**: TELUS Convention Centre
- **Centre Address**: 136 8 Ave SE
- **Individuals**: [Individual (1)]
- **Workers**: [Social Worker (1)]
- **Supplies**: [Supplies (1)]
- **Centre Logs**: [CentreLog (1)]

### Centre (2)
- **Centre Name**: University of Calgary
- **Centre Address**: 2500 University Dr NW
- **Individuals**: [Individual (2)]
- **Supplies**: [Supplies (2), Supplies (3)]
- **Centre Logs**: [CentreLog (2)]

## Supply Records

### Supplies (1)
- **id**: 500001
- **Type**: Medical Kit
- **Quantity**: 1

### Supplies (2)
- **id**: 500002
- **Type**: Personal Toiletries Kit
- **Quantity**: 1

### Supplies (3)
- **id**: 500005
- **Type**: Clothing Sets
- **Quantity**: 2

## Social Worker Records

### Social Worker (1)
- **id**: 600001
- **Name**: [Name of social worker]
- **Assigned Individuals**: [Individual (1)]

## Centre Log Records

### CentreLog (1)
- **id**: 700001
- **Date Logged**: 2024-01-18
- **Individual Logged**: Individual (1)
- **Reason**: Broken arm and shelter

### CentreLog (2)
- **id**: 700002
- **Date Logged**: 2024-01-18
- **Individual Logged**: Individual (2)
- **Reason**: Looking for her son
