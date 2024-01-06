The Pet class has the following attributes: name, kind, species, age, color, and gender. It also has a constructor to initialize these attributes.
The PetAdoptionSystem class has a private attribute pets which is a vector of Pet objects. It also has a private attribute generated to track if random pets have been generated. The class includes several methods:

generateRandomName(): generates a random name for a pet.
********************************************************
generateRandomPets(): generates a vector of random Pet objects.
**************************************************************
displayMenu(): displays the menu for the pet adoption system.
**************************************************************
addPetForAdoption(): prompts the user to enter details for a new pet and adds it to the pets vector.
****************************************************************************************************
displayAvailablePetsForAdoption(): displays the pets available for adoption. If no pets have been generated yet, it calls generateRandomPets() to generate some.
****************************************************************************************************************************************************************
