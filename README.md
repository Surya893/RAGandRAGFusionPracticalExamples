# RAG & RAG Fusion Practical Examples

I published a paper on RAG Fusion on Towards AI, a blog with over 120,000 people reading it!

The paper discussed the following:
• First off, what is RAG?
• How does it work?
• Where does RAG need to improve right now?
• What are the limitations?

1. Single Query Dependency
2. Low Recall and Precision
3. Inability to Contextualize Queries
4. Hallucination of Information
   
• Introducing RAG-Fusion: How does it compensate for RAG's shortcomings?
• How does RAG Fusion handle ambiguity in user queries?
• What is RAG Fusion's working Mechanism? 

1. User Query (top right)
2. Generate Similar Queries (center):
3. Vector Search Queries (bottom left):
4. Reciprocal Rank Fusion (center bottom):
5. Re-ranked Results (below Reciprocal Rank Fusion):
6. Generative Output (final bottom stage):
   
• The Math Behind RAG Fusion

RRF Formula
Scoring Explanation

• How does the constant K affect the RFF Score?


• Benefits of RRF

• Where can we actually use RAG Fusion IRL?

• Advantages & Challenges of RAG Fusion


• How do I see the future of RAG Fusion?

• How does RAG Fusion handle large datasets effectively?

• What makes RAG Fusion's multi-query generation effective?

1. Capturing Different Perspectives
2. Widening the Search Space
3. Ambiguity Removal
4. Improving Relevance
5. Complementing RRF
   
Examples:
1. Detailed Explanation
Output:

2. Basic Query
Output:

3. Medium Query
Output:

4. Detailed Query
Output:

5. Complex Query with multiple aspects
Output:

Ok, so RAG's cool, and RAG Fusion's cooler. But what's after that?

1. Integrated Information Retrieval (IIR)
2. Multimodal Information Retrieval
3. Hybrid Search: Improved Techniques
4. Contextualized Knowledge Graphs
5. Reinforcement Learning for Query Optimization
6. Improved Reranking Algorithms
7. Zero-Shot and Few-Shot Learning Techniques
   
• What is MMR?

• Example Scenario of MMR:


• To Summarize (by Bard):


• References: How I Learnt this Concept
