1. # Question:
plan a trip to USA 
1. # Agent Details:
(embedding=all-miniLM-L12-v2,LLM Model=gpt-4.1-nano,retrieval=basic,chunking = paragraph/default, chunks = 388)
1. # Response:
Assistant: Absolutely! Planning a trip to the USA is an exciting adventure filled with diverse experiences! Here's a vibrant and inspiring outline to help you get started:

Must-See:
- Washington: Dive into history and culture with visits to the Natural History Museum and the iconic White House. Don't miss Great Falls Park for hiking, kayaking, or simply enjoying the serene natural beauty.
- New York City: Experience the bustling energy of the Big Apple! Cross the Brooklyn Bridge, explore world-famous landmarks, and immerse yourself in the vibrant arts, theatre, and dining scenes.

Best Time to Visit:
- The USA offers year-round travel opportunities, but consider visiting Washington in spring or fall for pleasant weather and beautiful scenery. New York City is lively all year, with spring and fall being particularly charming due to mild temperatures and colorful foliage.

Tips:
- When visiting Washington, try to book White House tours well in advance as they can fill up quickly.
- For New York City, plan your itinerary based on your interests—whether it’s iconic sightseeing or exploring hidden underground gems.
- Flights from Australia typically go through Los Angeles, so plan accordingly.

Budget Estimate:
- Accommodation, food, and activities vary widely depending on your style, but a mid-range trip might start around AUD 2,500-3,500 per week for a comfortable experience.

Sources:
- [1] data\USA.pdf (Page 3)
- [2] data\USA.pdf (Page 1)
- [3] data\USA.pdf (Page 48)
- [4] data\USA.pdf (Page 27)
- [5] data\USA.pdf (Page 50)

Get ready for an unforgettable journey filled with adventure, culture, and inspiration!

2. # Question:
plan a trip to USA
2. # Agent Details:
(embedding=all-miniLM-L12-v2,LLM Model=gpt-4.1-mini,retrieval=MMR,chunking = paragraph/default, chunks = 388)
2. # Response:
Assistant: Planning a trip to the USA promises an adventurous, educational, inspirational, and remarkable experience! Here's a guide to help you make the most of your visit:

Must-See:
- Washington D.C.: Dive into history and culture by visiting iconic landmarks such as the Washington Monument—the world’s tallest stone structure—and the White House, where you can participate in special events on the grounds. Don’t miss the Natural History Museum, one of the most exciting attractions in the capital.
- Chicago: Explore the Magnificent Mile, a vibrant 13-block stretch along Michigan Avenue filled with over 460 shops and 275 restaurants. Enjoy a scenic walk through the heart of the city. If you visit during Christmas, experience the magical Lights Festival and ice carving competitions.
- Los Angeles: Often the gateway to the USA for Australian travelers, it’s your starting point to explore countless possibilities across the country.

Wine & Dine:
- In Washington D.C., savor delicious meals at AMBAR Capitol Hill, where the Balkan panini and cheese pie come highly recommended (make reservations in advance!). Also, check out COMMISSARY for an eclectic menu and fantastic pizza served by excellent staff.

Best Time to Visit:
- Christmas time in Chicago is spectacular with festive events on the Magnificent Mile.
- The time of year you visit greatly affects your experience, so plan according to the seasonal events and your interests.

Tips:
- Research extensively to decide which states and cities to prioritize since the USA offers limitless options.
- Make dining reservations in popular spots like AMBAR Capitol Hill to ensure a spot.
- Take advantage of public spaces like the Skywalk for stunning views paired with a coffee or cocktail at Lavazza café and bar.
- Consider combining urban exploration with outdoor activities such as hiking, picnicking, kayaking, or rock climbing to enjoy the country's natural serenity.

- Research extensively to decide which states and cities to prioritize since the USA offers limitless options.
- Make dining reservations in popular spots like AMBAR Capitol Hill to ensure a spot.
- Take advantage of public spaces like the Skywalk for stunning views paired with a coffee or cocktail at Lavazza café and bar.
- Consider combining urban exploration with outdoor activities such as hiking, picnicking, kayaking, or rock climbing to enjoy the country's natural serenity.

- Take advantage of public spaces like the Skywalk for stunning views paired with a coffee or cocktail at Lavazza café and bar.
- Consider combining urban exploration with outdoor activities such as hiking, picnicking, kayaking, or rock climbing to enjoy the country's natural serenity.

- Consider combining urban exploration with outdoor activities such as hiking, picnicking, kayaking, or rock climbing to enjoy the country's natural serenity.

njoy the country's natural serenity.


Budget Estimate:
While specific costs are not provided, expect varied expenses depending on cities and activities. Dining at recommended restaurants and visiting major attractions may require moderate to high budgets, especially during peak seasons like Christmas.
While specific costs are not provided, expect varied expenses depending on cities and activities. Dining at recommended restaurants and visiting major attractions may require moderate to high budgets, especially during peak seasons like Christmas.
staurants and visiting major attractions may require moderate to high budgets, especially during peak seasons like Christmas.

Get ready for an unforgettable journey through the diverse landscapes and vibrant cultures of the United States!

Sources:
- [1] USA.pdf (Pages 1, 3, 15, 48, 53)

3. # Question:
plan a trip to USA
3. # Agent Details:
(embedding=all-miniLM-L12-v2,LLM Model=gpt-4.1-mini,retrieval=Similarity search,chunking = paragraph/default, chunks = 388)
3. # Response:

Notes:
- UNEXPECTED    :can be ignored when loading from different task/architecture; not ok if you expect identical arch.       
D:\Agentic AI projects\Assignments\RAG_AI_Agent_Assignment\rag_agent.py:132: LangChainDeprecationWarning: The class `Chroma` was deprecated in LangChain 0.2.9 and will be removed in 1.0. An updated version of the class exists in the `langchain-chroma package and should be used instead. To use it run `pip install -U `langchain-chroma` and import as `from `langchain_chroma import Chroma``.
  vector_store = Chroma(
    Score: 0.538 | data\USA.pdf
    Score: 0.536 | data\USA.pdf
    Score: 0.091 | data\USA.pdf
    Score: 0.086 | data\USA.pdf
    Score: 0.083 | data\USA.pdf
  [Retrieve] Found 2 relevant chunks for: 'plan a trip to USA'
    [1] data\USA.pdf (Page 3)
    [2] data\USA.pdf (Page 1)
  [Generate] Answer produced.

Assistant: Planning a trip to the United States promises an adventurous, educational, inspirational, and remarkable experience! Here's a guide to help you get started:

Must-See:
- Los Angeles: Often the gateway for Australian travelers, this vibrant city offers iconic attractions like Hollywood, beautiful beaches, and diverse cultural experiences.
- Beyond LA: With over 50 states to explore, the USA offers limitless possibilities. Whether you seek bustling cities, national parks, or unique small towns, there's something for everyone.

Best Time to Visit:
- The time of year you visit will dramatically affect your experience. Researching the climate and events in your chosen destinations will help you pick the perfect season.

Tips:
- Since the USA is vast, plan your itinerary based on your interests—whether it's city life, nature, or cultural experiences.
- Extensive research on states and cities is recommended to tailor your trip to your preferences.

Budget Estimate:
- Not specified in the available information.

Embark on your American adventure with excitement and an open mind—there’s truly no limit to the experiences awaiting you!

Sources:
- USA Travel Guide, Pages 1 and 3 (data\USA.pdf)

4. # Question:
plan a trip to USA
4. # Agent Details:
(embedding=all-miniLM-L12-v2,LLM Model=gpt-4.1-mini,retrieval=Basic,chunking = token text splitter, chunks = 164)
4. # Response:
Assistant: Planning a trip to the United States promises an adventurous, educational, inspirational, and remarkable experience! Here's a guide to help you get started:

Must-See:
- Los Angeles: Often the gateway for Australian travelers, this vibrant city offers iconic attractions like Hollywood, beautiful beaches, and diverse cultural experiences.
- Beyond LA: With over 50 states to explore, the USA offers limitless possibilities. Whether you seek bustling cities, national parks, or unique small towns, there's something for everyone.

Best Time to Visit:
- The time of year you visit will dramatically affect your experience. Researching the climate and events in your chosen destinations will help you pick the perfect season.

Tips:
- Since the USA is vast, plan your itinerary based on your interests—whether it's city life, nature, or cultural experiences.
- Extensive research on states and cities is recommended to tailor your trip to your preferences.

Budget Estimate:
- Not specified in the available information.

Embark on your American adventure with excitement and an open mind—there’s truly no limit to the experiences awaiting you!

Sources:
- USA Travel Guide, Pages 1 and 3 (data\USA.pdf)

------------------------------------`Observations`------------------------------------
## Data Ingestion
- As the documents consist smaller paragraphs, tokens(164) are lesser for token splitter comparatively with paragraph/ new line splitter, tokens(388)

## Response Evaluation
- Model gpt-4.1-mini with token split chunking of 164 chunks given broader plan comparatively with other settings
- Model gpt-4.1-mini with default paragraph chunking of 388 chunks using similarity search had retrieved lesser chunks(2) comparatively with all other retrievals chunks(5)