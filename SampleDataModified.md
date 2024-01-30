# Disaster Relief Sample Data

## Individual Records

### Individual (1)
- **name**: Teruya
- **gender**: Male
- **id**: 100001
- **age**: 5
- **height**: 43 inches
- **weight**: 38 pounds
- **appearance**: Black hair, brown eyes
- **dateOfBirth**: Unknown
- **familyMembers**: Family (1)
- **currentLocation**: TELUS Convention Centre (Centre 1)
- **relationships**: Unknown
- **minor**: True
- **medInfo**: Medical (1)

### Medical (1)
- **injuries**: [Broken arm]
- **treatment**: [Cast applied]
- **dateOfCare**: 2024-01-18

### Individual (2)
- **name**: Freda McDonald
- **gender**: Female
- **id**: 100002
- **age**: 38
- **height**: 72 inches
- **weight**: 112 pounds
- **appearance**: Unknown
- **dateOfBirth**: 1986-06-03
- **familyMembers**: Family (1)
- **currentLocation**: University of Calgary (Centre 2)
- **relationships**: Husband - Jo Bouillon (Not in system), Children - Teruya (Individual 1)
- **minor**: False
- **medInfo**: Medical (2)

### Medical (2)
- **injuries**: [Twisted ankle, Light burns]
- **treatment**: [Ankle wrap, Burn treatment]
- **dateOfCare**: 2024-01-18


## Family Records

### Family (1)
- **id**: 200003
- **members**: [Individual (1), Individual (2)]

## Centre Records

### Centre (1)
- **centreName**: TELUS Convention Centre
- **centreAddress**: 136 8 Ave SE
- **centreOccupants**: [Individual (1)]
- **centreWorkers**: [Social Worker (1)]
- **cuppliesList**: [Supplies (1)]
- **centreLogs**: [CentreLog (1)]

### Centre (2)
- **centreName**: University of Calgary
- **centreAddress**: 2500 University Dr NW
- **centreOccupants**: [Individual (2)]
- **centreWorkers**: []
- **suppliesList**: [Supplies (2), Supplies (3)]
- **centreLogs**: [CentreLog (2)]

## Supply Records

### Supplies (1)
- **id**: 500001
- **type**: Medical Kit
- **quantity**: 1

### Supplies (2)
- **id**: 500002
- **type**: Personal Toiletries Kit
- **quantity**: 1

### Supplies (3)
- **id**: 500005
- **type**: Clothing Sets
- **quantity**: 2

## Social Worker Records

### Social Worker (1)
- **id**: 600001
- **name**: [Name of social worker]
- **assignedIndividuals**: [Individual (1)]

## Centre Log Records

### CentreLog (1)
- **id**: 700001
- **dateLogged**: 2024-01-18
- **individualLogged**: Individual (1)
- **reason**: Broken arm and shelter

### CentreLog (2)
- **id**: 700002
- **dateLogged**: 2024-01-18
- **individualLogged**: Individual (2)
- **reason**: Looking for her son
