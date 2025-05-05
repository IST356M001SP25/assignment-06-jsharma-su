# Reflection

Student Name:  Jiya Sharma
Sudent Email:  jsharma@syr.edu

## Instructions

Reflection is a key activity of learning. It helps you build a strong metacognition, or "understanding of your own learning." A good learner not only "knows what they know", but they "know what they don't know", too. Learning to reflect takes practice, but if your goal is to become a self-directed learner where you can teach yourself things, reflection is imperative.

- Now that you've completed the assignment, share your throughts. What did you learn? What confuses you? Where did you struggle? Where might you need more practice?
- A good reflection is: **specific as possible**,  **uses the terminology of the problem domain** (what was learned in class / through readings), and **is actionable** (you can pursue next steps, or be aided in the pursuit). That last part is what will make you a self-directed learner.
- Flex your recall muscles. You might have to review class notes / assigned readings to write your reflection and get the terminology correct.
- Your reflection is for **you**. Yes I make you write them and I read them, but you are merely practicing to become a better self-directed learner. If you read your reflection 1 week later, does what you wrote advance your learning?

Examples:

- **Poor Reflection:**  "I don't understand loops."   
**Better Reflection:** "I don't undersand how the while loop exits."   
**Best Reflection:** "I struggle writing the proper exit conditions on a while loop." It's actionable: You can practice this, google it, ask Chat GPT to explain it, etc. 
-  **Poor Reflection** "I learned loops."   
**Better Reflection** "I learned how to write while loops and their difference from for loops."   
**Best Reflection** "I learned when to use while vs for loops. While loops are for sentiel-controlled values (waiting for a condition to occur), vs for loops are for iterating over collections of fixed values."

`--- Reflection Below This Line ---`

Working on Assignment 06 offered me valuable hands-on experience in building and managing a multi-step ETL (Extract, Transform, Load) pipeline that interacts with external APIs. This assignment emphasized how real-world data applications are often modular, and that breaking tasks into manageable, sequential steps makes development and debugging significantly easier.

The most rewarding part of this assignment was learning how to structure an ETL pipeline using both Google and Azure APIs. I appreciated the logic of transforming raw review data into structured insights by combining API calls, JSON parsing, and Pandas data manipulation. Writing reusable and testable functions for each stage—reviews_step, sentiment_step, and entity_extraction_step—helped me understand the importance of clean interfaces between stages in a data pipeline.

One of the main challenges I faced was managing API quotas and ensuring I didn’t accidentally overuse the resources while testing. I learned the value of caching intermediate results, which allowed me to continue developing and testing downstream processes without repeating expensive API calls. This principle of caching and reusability is something I now recognize as essential in any large-scale data pipeline.

Another challenge was working with nested JSON responses. While json_normalize proved helpful, I still had to carefully inspect the API response formats and flatten them correctly while preserving necessary context like place_id and author_name. This taught me how critical it is to fully understand the structure of data coming from external services before trying to manipulate it.

Overall, this assignment not only strengthened my Python skills but also deepened my understanding of API integration, data wrangling, and building scalable data pipelines. It has prepared me for more advanced analytics tasks where automation, performance, and modularity are key.