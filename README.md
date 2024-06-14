# Sales Conversations Dataset Generation

## Research Context

In the domain of Language Models and generative AI, the ability to produce coherent and contextually relevant conversations is an area of significant interest. This project is inspired by the research paper "Let the LLMs Talk" (2312.02913 on arXiv.org), which explores the potential of Language Models to engage in diverse and meaningful conversations. The goal here is to create an extensive dataset of sales conversations, simulating interactions between a salesperson and a potential customer.

## Performance Evaluation Criteria and Grading Rubric

### Minimum Data Size Requirement
Each submission should include a minimum of 100 sets of dialogues. Each dialogue set should consist of up to 5 exchanges between the salesperson and the customer, with each response comprising 50-75 words.

### Data Quality
1. **Contextual Relevance and Understanding**: Conversations should revolve around sales scenarios, demonstrating a deep understanding of the products or services being offered.
2. **Coherence, Fluency, and Readability**: Responses should flow smoothly, exhibit grammatical accuracy, and adhere to principles of effective communication.
3. **Creativity and Engagement**: Conversations should be engaging, showcasing creativity in presenting the product or service and capturing the interest of potential customers.
4. **Toxicity and Bias Mitigation**: Dialogues must be free from toxic language, personal attacks, and discriminatory content. Participants should actively mitigate bias and stereotypes and promote inclusive language.
5. **Accuracy and Completeness of Information**: Information provided in the sales pitch should be accurate, truthful, and complete, avoiding any misleading or incomplete statements.

### Number of Products Sold
A key metric for evaluation is the number of products or services 'sold' through effective sales conversations. Participants should aim to maximize this metric by crafting compelling and persuasive dialogues.

### Compute Time
The time taken to generate the dataset will also be considered. Lower compute times per dialogue indicate higher efficiency and will be rewarded accordingly.

### Bonus for Data Size Increment
Participants will receive bonus points for generating datasets larger than the minimum requirement. For every additional 10 sets of dialogues, participants will earn incremental bonus points, encouraging comprehensive contributions.

## Submission Format

Each submission should include the following files:

1. **sales_conversations.csv**: A CSV file containing the generated sales conversations, with columns for 'Salesman', 'User', and 'Timestamp'.
2. **README.md**: A Markdown file providing clear instructions for running the code, understanding the evaluation criteria, and any additional details deemed necessary.

## Usage

To generate the sales conversations dataset, follow these steps:

1. Run the `run.py` script.
2. Adjust parameters such as the number of dialogue sets and the word count range as needed.
3. The script will generate the dataset and save it to the `sales_conversations.csv` file.

