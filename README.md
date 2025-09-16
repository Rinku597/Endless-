# Endless

(**New folder**)  

**the role**
here our first role is G1

**OG**
there is so many og role in discord 
import hashlib
import json
from time import time

class Block:
    def __init__(self, index, timestamp, data, previous_hash):
        self.index = index
        self.timestamp = timestamp
        self.data = data
        self.previous_hash = previous_hash
        self.hash = self.calculate_hash()

    
