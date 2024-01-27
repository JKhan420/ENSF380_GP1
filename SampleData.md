Centre(1)...
centreName: University of Calgary
centreAddress: 2500 University Dr NW
centreOccupants: Individual(1)

Individual(1)...
name: Freda McDonald
gender: female
id: 001 
dateOfBirth: 1986-06-03
medInfo: Medical(1)
familyMembers: Family(1)

# Note: even though we arent provided with ID info, it would be easier to track someone this way in case some shares the same name

Medical(1)...
injuries: - Twisted ankle
          - Light Burns
supplies: - Toiletries kit
          - Two sets of clothes
treatment: - Ankle has cast
           - burns been bandaged

# NOTE: even though we arent given treatment info, would be very useful for family members that are searching for someone in case if they wanted to know they have been treated and are doing alright

Family(1)...
members: - Teruya Jari
         - Luis Bouillon