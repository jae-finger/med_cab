# med_cabinet_4
## Product Vision: Med Cabinet 4
### ☝️ Proposal
#### What problem does your app solve?
Help patients find the right strains of cannabis, dosing, intake method and intake schedule.
Be as specific as possible; how does your app solve the problem?
Website is going to provide a platform for finding this and recommends dispensaries, DS provides the recommendations.  Think Automated budtender.

#### What is the mission statement?
Platform for recommending strains as though an automated budtender.

### 💡 Features

#### What features are required for your minimum viable product?
1. User creation & Login
2. Strain Recommender
3. Save Recommendations

#### What features may you wish to put in a future release?
Online delivery service?

#### What do the top 3 similar apps do for their users?
1. WeedMaps -- Locate dispensaries, strains, deals, learn, deliveries, maps
2 .Leafly -- Find/Recommend strains | Locate dispensary and info (menu, location, hours) | Buy product and keep history/cart
3. Bud.com

### 🛠 Frameworks - Libraries

#### What 3rd party frameworks/libraries are you considering using?
Flask
Requests
React
Axios
Express 
Knex
PostgreSQL 
JWT
Styled components
Redux
React Forms

#### Do the APIs you need require you to contact them to gain access?
Data scraping
Kaggle
Data.World

#### Are you required to pay to use said API(s)?
No 

### 🧮 For Data Scientists

#### Describe the established data source with at least rough data able to be provided on day one.
Kaggle
Data.World

#### Write a description for what the data science problem is. What uncertainty or prediction are you trying to discover? How could this data be used to find a solution to this problem?
Matching what a user wants (dosing, effects, intake) and recommending based on a data source of strain information and reviews. The DS model predicts the strain that matches what the user wants and returns a strain and other info

#### What kind of target output can you deliver to the Web/UX/iOS teams to work with? Is it in JSON format or something else?
	JSON      Web -> JSON {type: indica…}    DS -> JSON {strain: pineapple express, dosing: everyday}

### 🎯 Target Audience

#### Who is your target audience? Be specific.
Patients new to medical cannabis, seeking recs.

#### What feedback have you gotten from potential users?
The information is helpful but I would like to have a product specialist to consult with. 

#### Have you validated this problem and your solution with a target audience? Describe how,

### 🔑 Prototype Key Feature(s)

### How long do you think it will take to implement these features?
2 weeks

#### Do you anticipate working on stretch functionality after completion of a Minimal Viable Product?
Maybe, more likely yes
Tuning hyperparameters after model works baseline