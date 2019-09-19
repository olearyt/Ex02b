 | PetID | Pet Name | PetType |    PetBreed | PetDOB    | OwnerEmail                  |
 |:-----:|----------|:-------:|------------:|-----------|-----------------------------|
 |   1   | King     |   Dog   | Std. Poodle | 27-Feb-14 | Marsha.Downs@somewhere.com  |
 |   2   | Teddy    |   Cat   |    Cashmier | 1-Feb-13  | Richard.James@somewhere.com |
 |   3   | Fido     |   Dog   | Std. Poodle | 17-Jul-15 | Marsha.Downs@somewhere.com  |
 |   4   | AJ       |   Dog   | Collie Mix  | 5-May-15  | Liz.Frier@somewhere.com     |
 |   5   | Cedro    |   Cat   | Unknown     | 6-Jun-12  | Richard.James@somewhere.com |
 |   6   | Wolley   |   Cat   | Unknown     | ???       | Richard.James@somewhere.com |
 |   7   | Buster   |   Cat   | Unknown     | 11-Dec-11 | Miles.Trent@somewhere.com   |
 |   8   | Jiddah   |   Cat   | Abyssinian  | 1-Jul-08  | Hilary.Evans@somewhere.com  |

| OwnerEmail                  | OwnerLastName | OwnerFirstName |  OwnerPhone  |
|-----------------------------|:-------------:|:--------------:|:------------:|
| Marsha.Downs@somewhere.com  |     Downs     |     Marsha     | 201-823-5467 |
| Richard.James@somewhere.com |     James     |     Richard    | 201-735-9812 |
| Liz.Frier@somewhere.com     |     Frier     |       Liz      | 201-823-6578 |
| Miles.Trent@somewhere.com   |     Trent     |      Miles     | 201-634-7865 |
| Hilary.Evans@somewhere.com  |     Evans     |     Hilary     | 201-634-2345 |

| Service           |    Date   |  Charge | OwnerEmail                  |
|-------------------|:---------:|--------:|-----------------------------|
| Ear Infection     |17-Aug-16  | $65.00  | Marsha.Downs@somewhere.com  |
| Nail Clip         | 5-Sep-16  | $27.50  | Richard.James@somewhere.com |
| One Year Shots    | 5-May-16  | $42.50  | Liz.Frier@somewhere.com     |
| Nail Clip         | 5-Sep-16  | $27.50  | Richard.James@somewhere.com |
| Skin Infection    | 3-Oct-16  | $35.00  | Richard.James@somewhere.com |
| Laceration Repair | 5-Oct-16  | $127.00 | Miles.Trent@somewhere.com   |
| Booster Shots     | 4-Nov-16  | $111.00 | Hilary.Evans@somewhere.com  |

# Step 1
Identify the candidate keys of this relation. The candidate keys are PetName, OwnerEmail, & PetDOB

# Step 2
Next we identify all of the functional dependencies. OwnerEmail is a determinant of OwnerFirstName, OwnerLastName, & OwnerPhone.
PetDOB is a determinant of PetBreed, PetType, & PetName. Service is a determinant of the Date & Charge. 

# Step 3
We used OwnerEmail as a foreign key for both the Pet relation and the Service relation. 
We did not use a foreign key for the Owner relation because the number of rows are not consistent through the relations. 
