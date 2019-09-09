# NewPets

### Front Page
- sign up free points link
- news carousel
- link to popular game
- search? (items)
- friends online (last seen recently)
- ???

### Page List
- NewPets location maps with links to games (area and map html elements(image-map.net))
- games to win NewPoints
- a shop to spend NewPoints in 
- NewPet create
- NewPet show
- NewPet update (delete = orphanage)
- orphanage (adopt pets)
- user show page (inventory, pets, friends)
- search results display

### Models
- Users
  - username
  - password
  - points
  - last seen
  - friends (polymorphic)
- Pets (static)
  - image
  - species
- UserPets (join)
  - user_id
  - pet_id
  - name
  - Mood
  - lastEaten
  - Age
  - Level
- Items
  - name
  - description
  - image
  - type?
- UserItems(inventory)
  - userId
  - itemId
- News
  - title
  - content
  - image

  # Pixel Positions 
   - Aspen: Write tests 
   - Lucy: Location Maps and Page Games (ex: Ice Caves, daily events and random event)
   - Hal: ??????? & games
   - Katie: Games (TYPING TERROR) & overall lore
   - Mari: All the fabulous art!!

   