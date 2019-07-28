<h1> Engineering Block Chain Project - Water pipe projects referral </h1>

<br>

This is a technical design part for the engineering block chain for water pipe projects referral purpose.

The water pipe projects referral is our first example in our engineering block chain portfolios

<br>

The offical website of our engineering block chain is defined at website at http://www.coengineers.io

The white paper https://coengineers.io/publications/CoEngineers_Whitepaper.pdf explains the full vision


<br>



<h2> Data Schema Design for water pipe project</h2>

Every water pipe project in any building has a file called water pipe system definition file.

We are trying to capture the key meta info of such a file into a json file which has following sample format:

```

{

"project name"      : "Sunset Plaza Apartments - Plumbing System Definition",
"year built"        : 1962,
"project year"      : 2015,
"general contractor": "Community Engineering Services, PLLC",
"license"           : "CA #30667M",
"chief engineer"    : "Daniel R. Robles",
"contact phone"     : "425-361-8499" ,
"contact email"     : "dan@coengineers.com" ,
"project reference id"  :  " ",
"block record id"       : " ",
"block record type"     : "water pipe system definition",
"block record creator id": " ",
"block record created on" : " ",
"block record last updated on" : " ",
"block record last revision tag": " ",
"plumbing system definition": " https://www.coengineers.com/wp-content/uploads/2015/04/Sunset-Plaza-R5.pdf",
"general info" :
        {
            "building address"  : "1234 Cameron Avenue, West Covina, CA",
            "style"             : "Garden Apartments",
            "building sqft"     : 109333,
            "land size in ac"   : 4.33, 
            "total units"       : 183,
            "average unit SF"   : 911,
            "number of floors"  : [
                {
                "building no": 1,
                "floors"     : 2 
                },
                {
                "building no": 2,
                "floors"     : 2 
                },
                {
                "building no": 3,
                "floors"     : 2 
                },
                {
                "building no": 4,
                "floors"     : 2 
                },
                {
                "building no": 5,
                "floors"     : 1 
                }
            ],
            "parking spaces" : 222,
            "year plumbing built"     : 1962,
            "parcel number" : "8469-001-012",
            "zoning "       : "R3-MF20",
            "assessors office":
                {
                    "permit contact": "626-256-6001"
                }
        },
    "amenities" : {
        "unit amenities" : [
            "balconies",
            "microwave",
            "storage units",
            "ceiling fans",
            "granite countertops",
            "wood floors",
            "walk-in closets",
            "carports"
            ],
        "site amenities" : [
            "business center",
            "clubhouse",
            "fitness center with washroom",
                "laundry 1",
                "laundry 2",
                "laundry 3",
                "laundry 4",
            "picnic area",
				"pool 1, unheated with water treatment vales", 
				"pool 2, unheated with water treatment vales", 
				"pool 3, heated and has spa",
            "game room",
            "grill",
            "laundry service",
            "pet play area",
            "planned social activies",
            "has elevator"
            ]
        },
        "dimensions":[
            {
                "building address"  : "800 South Sunset Ave",
                "total floors"      : {
                    "garden floor in ft": "150x30",
                    "floor 1 in ft"     : "230x130",
                    "floor 2 in ft"     : "230x130",
                    "floor 3 in ft"     : "230x130"
                },
                "floor height in ft"    : 10,
                "building height in ft" : 30
            },
            {
                "building address"  : "1242 Cameron Ave",
                "total floors"      : {
                    "garden floor in ft"     : "70x30",
                    "floor 1 in ft"     : "150x120",
                    "floor 2 in ft"     : "150x120"
                },
                "floor height in ft"    : 10,
                "building height in ft" : 20
            },
            {
                "building address"  : "1238 Cameron Ave",
                "total floors"      : {
                    "garden floor in ft"     : "70x30",
                    "floor 1 in ft"     : "150x120",
                    "floor 2 in ft"     : "150x120"
                },
                "floor height in ft"    : 10,
                "building height in ft" : 20
            },
            {
                "building address"  : "1232 Cameron Ave",
                "total floors"      : {
                    "garden floor in ft"     : "100x60",
                    "floor 1 in ft"     : "180x150",
                    "floor 2 in ft"     : "180x150"
                },
                "floor height in ft"    : 10,
                "building height in ft" : 20
            },
            {
                "building address"  : "1230 Cameron Ave",
                "total floors"      : {
                    "floor 1 in ft"     : "150x190",
                    "floor 2 in ft"     : "150x190"
                },
                "floor height in ft"    : 10,
                "building height in ft" : 20
            }

        ],
        "interior finishes" : "commercial grade",
        "has drywall"           : true,
        "has plaster wall"      : true,
        "floorings" :   {
            "has laminate"  :   true,
            "has tile"      :   true,
            "has carpeting" :   true,
            "has care concrete" : true
        },
        
        "access":{
            "has interior construction space"   : false,
            "construction parking space"    : {
                "has parking for construction"  : true,
                "total construction parking space" : 6
            }
        },     
        "shared elevator time for construction" : true,
        "exclusive elevator time for construction " : true,
        "elevator space " : "6 ft x 6 ft x 7 ft tall",

        "hazardous materials":{
            "asbestors" : true,
            "asbestor report done" : true,
            "lead based paints": true,
            "lead paint report done" : false,
            "hazardous materials testing done by sample" : true
        },
        "maintenance records":{
            "plumbing system work order log available" : true,
            "total month of past logs"    : 24,
            "logs failures":[
                "water pressure failre",
                "clogged pipes",
                "pinhole leaks",
                "raptures"
            ],
            "failure reasons":[
                "inner corrosion of the pipes",
                "rust nodules clogging pipes"
            ]
        },
        "building construction elements":[
            "constructed on concrete slab on grade",
            "wooden truss ceiling",
            "no structure below grade",
            "parking on 2 sides",
            "common floor plans",
            "common wet walls"
        ],
        "existing pipes":{
            "lateral water piping":{

            },
            "risers" :{

            },
            "routing":{

            },
            "other descriptions": "There is lateral water pipingrunning below slab in the 2-­‐storey buildings that may    need to be re-­‐routed. Management notes hot spots on the concrete floor. Hybrid routing of cold and hot water    was evident in the 3-­‐storey building. Water supply was connected to fire hose cabinets in 3-­‐storey building and landscape irrigation systems throughout the complex. Multiple street water connections on Cameron Ave.were observed. It was not possible to locate and count all risers and laterals without exploratory removal of walls, however, due to the layout of the buildings it seems that some type of ring system would/should feed floors collectively or individually where a single take-­‐off riser may serve up to 4 units. In the case of the 3-­‐storey building, one riser may serve 6 units. Ceiling height measured approximately 9 ft from the floor with a 1-­‐foot  truss space. In general, the units stack vertically throughout the 5 buildings with the exception of    amenity spaces and the town homes. There are no penthouse units or    substantially unique floor plans. There are reported to be 26 unique unit    plans. There are 49 exterior hose bibs.The property has experienced pipe    breaks and rust in the water. The predominantly galvanized plumbing system    has exceeded its reliable service life and must be considered fragile.            Cascading failures is a condition where additional damage occurs in the    process of repairing a segment of pipe and must be avoided."
        },

        "floor plans":{

        },

        "pipe materials":{

        },
     
        "engineering considerations":[
            "Currently exhibiting rust in water (yellow water)",
            "Currently exhibiting pressure variations",
            "Currently requires periodic cleanout where rust clogs a line",
            "Boilers system age and efficiency may warrant review•Significant redesign", required to meet code requirements",
            "Dual hybrid system: cold lines are separate system than hot lines",
            "Each unit may require separate shut off valves",
            "New routing may be required for code provisions",
            "Irrigation system cross connection control required",
            "Integration with fire systems",
            "Pool,Spa,and common areas"
        ],

        "conclusions":[
            " The domestic water system in the Sunset Plaza Apartment complex has reached the end of its useful life.",
            " A like-­‐for-­‐like replacement of the system is probably not be possible given new codes and under slab routing.",
            " A modern design will be required with proper integration to irrigation system and fire safety components.",
            " General dimensions, quantities, and photo documentation is included in this report to assist in the renovation of this aging domestic water system. "
        ]
    
}
```