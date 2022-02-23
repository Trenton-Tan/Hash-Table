Program written in Python
  Takes 2 command line inputs
    Percentage of hash table that is filled (input as a number from 0-1.0)
    Hashing scheme used

Implemented 3 schemes of hashing to determine which variation led to the least amount of collisions 
  Standard Hashing
    Use hashing function to compute slot
      Used function randint() to get a random integer 
        Set limits from 0 to 1 less than the total number of slots
    Only compute one slot number regardless of slot current occupancy
  2-choice Hashing
    Use 2 hash functions to find 2 slot numbers --> pick slot with less occupancy (break ties randomly)
  2-left Hashing
    Split hash table into 2 equal subtables
    Use independent hash functions, one for each subtable, to find two slots to hash to
      Choose less occupied slot (always break ties towards one subtable)
    

