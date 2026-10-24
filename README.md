This README will be used for documentation

Draft Categories List

Theme Park Recommendation Engine

│

├── 1. Age Groups

│   ├── Toddlers (<5)

│   ├── Kids (5-12)

│   ├── Teens (13-17)

│   ├── Adults (18-59)

│   └── Seniors (60+)

│

├── 2. User Interests

│   ├── Thrill & Adventure

│   ├── Family & Sightseeing

│   ├── Immersive & Shows

│   └── Relaxation & Calming

│

├── 3. Cost

│   ├── Free

│   ├── Moderate ($10-$30)

│   └── Premium ($30+)

│

└── 4. Queue Time (Real-Time)

    ├── Short (<15m)
    
    ├── Medium (15-45m)
    
    ├── Long (45m+)
    
    └── Express Available
    

List of Attraction Names:

Siloso Rush Coaster

Palawan Family Splash Carousel

Lazarus Lagoon Kayak Safari

Sentosa Wave VR Simulator

East Coast Sunset Cruise

Tanjong Beach Mega Plunge

Changi Coast Mystery Cave

Southern Isles Observatory Tower

Pasir Ris Aqua Stunt Show

Mega Zip Coastal Freefall


Categorisation:

🏖️ Beach Theme Park Recommendation Engine

│

├── 👥 1. Age Groups Filter

│   ├── 👶 Toddlers (<5)

│   │   └── Palawan Family Splash Carousel, Southern Isles Observation Tower, Pasir Ris Aqua Stunt Show

│   ├── 🧒 Kids (5-12)

│   │   └── Palawan Carousel, Lazarus Kayak Safari, Tanjong Beach Mega Plunge, Changi Mystery Cave, etc.

│   ├── 👦 Teens (13-17)

│   │   └── Siloso Rush Coaster, Lazarus Kayak, Sentosa Wave VR, Tanjong Plunge, MegaZip Freefall, etc.

│   ├── 👨 Adults (18-59)

│   │   └── Siloso Rush Coaster, Sentosa Wave VR, East Coast Sunset Cruise, MegaZip Freefall, etc.

│   └── 🧓 Seniors (60+)

│       └── Palawan Carousel, East Coast Sunset Cruise, Southern Isles Tower, Pasir Ris Aqua Show

│

├── 🎯 2. User Interests Filter

│   ├── ⚡ Thrill & Adventure

│   │   └── Siloso Rush Coaster, Sentosa Wave Simulator VR, Tanjong Beach Mega Plunge, MegaZip Coastal Freefall

│   ├── 👨‍👩‍👧 Family & Sightseeing

│   │   └── Palawan Carousel, Lazarus Lagoon Kayak, Changi Coast Mystery Cave, Pasir Ris Aqua Show

│   ├── 🔭 Immersive & Shows

│   │   └── Lazarus Lagoon Kayak, East Coast Sunset Cruise, Southern Isles Tower, Pasir Ris Aqua Show

│   └── 🌴 Relaxation & Calming

│       └── Palawan Family Splash Carousel, East Coast Sunset Cruise, Southern Isles Observation Tower

│
├── 💳 3. Cost Filter

│   ├── 🟢 Free / Included ($0)

│   │   └── Siloso Coaster, Palawan Carousel, East Coast Cruise, Tanjong Plunge, Changi Cave, Pasir Ris Show

│   ├── 🟡 Moderate ($10 - $15)

│   │   └── Lazarus Lagoon Kayak Safari, Southern Isles Observation Tower

│   └── 🔴 Premium ($35 - $40)

│       └── Sentosa Wave Simulator VR, MegaZip Coastal Freefall

│

└── ⏱️ 4. Real-Time Queue Time Filter

    ├── 🟢 Short (< 15 mins)
    
    │   └── Palawan Carousel, East Coast Cruise, Southern Isles Tower, Pasir Ris Show
    
    ├── 🟡 Medium (15 – 45 mins)
    
    │   └── Lazarus Kayak Safari, Changi Coast Mystery Cave, MegaZip Coastal Freefall

    ├── 🔴 Long (45+ mins)
    
    │   └── Siloso Rush Coaster, Tanjong Beach Mega Plunge
    
    └── ⚡ Express Available / Virtual Queue
    
        └── Sentosa Wave Simulator VR
        


Dictionary structure:

attractions = [

    {
    
        "name": "Siloso Rush Coaster",
        
        "age_groups": ["Teens", "Adults"],
        
        "interests": ["Thrill & Adventure"],
        
        "cost": "Free",
        
        "queue_time": "Long"
        
    },
    
    {
    
        "name": "Palawan Family Splash Carousel",
        
        "age_groups": ["Toddlers", "Kids", "Seniors"],
        
        "interests": ["Relaxation & Calming", "Family"],
        
        "cost": "Free",
        
        "queue_time": "Short"
        
    },
    
    {
    
        "name": "Lazarus Lagoon Kayak Safari",
        
        "age_groups": ["Kids", "Teens", "Adults"],
        
        "interests": ["Family", "Sightseeing"],
        
        "cost": "Moderate",
        
        "queue_time": "Medium"
        
    },
    
    {
    
        "name": "Sentosa Wave Simulator VR",
        
        "age_groups": ["Teens", "Adults"],
        
        "interests": ["Thrill & Adventure", "Immersive"],
        
        "cost": "Premium",
        
        "queue_time": "Express Available"
        
    },
    
    {
    
        "name": "East Coast Sunset Cruise",
        
        "age_groups": ["Adults", "Seniors"],
        
        "interests": ["Relaxation & Calming", "Sightseeing"],
        
        "cost": "Free",
        
        "queue_time": "Short"
        
    },
    
    {
    
        "name": "Tanjong Beach Mega Plunge",
        
        "age_groups": ["Kids", "Teens", "Adults"],
        
        "interests": ["Thrill & Adventure", "Family"],
        
        "cost": "Free",
        
        "queue_time": "Long"
        
    },
    
    {
    
        "name": "Changi Coast Mystery Cave",
        
        "age_groups": ["Kids", "Teens", "Adults"],
        
        "interests": ["Family", "Immersive"],
        
        "cost": "Free",
        
        "queue_time": "Medium"
        
    },
    
    {
        "name": "Southern Isles Observation Tower",
        
        "age_groups": ["Toddlers", "Kids", "Teens", "Adults", "Seniors"],
        
        "interests": ["Sightseeing", "Relaxation & Calming"],
        
        "cost": "Moderate",
        
        "queue_time": "Short"
        
    },
    
    {
    
        "name": "Pasir Ris Aqua Stunt Show",
        
        "age_groups": ["Toddlers", "Kids", "Teens", "Adults", "Seniors"],
        
        "interests": ["Sightseeing", "Family"],
        
        "cost": "Free",
        
        "queue_time": "Short"
        
    },
    
    {
    
        "name": "MegaZip Coastal Freefall",
        
        "age_groups": ["Teens", "Adults"],
        
        "interests": ["Thrill & Adventure"],
        
        "cost": "Premium",
        
        "queue_time": "Medium"
        
    }
    
]


Diagram Representation:

<img width="1024" height="559" alt="32541648-ca1d-424b-bfb1-b1f1109e4894" src="https://github.com/user-attachments/assets/9c7faa74-6766-485e-a099-aa946297b9d2" />
