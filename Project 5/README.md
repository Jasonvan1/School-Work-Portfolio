Objective:
To analyze consumer reviews of weight loss supplements, identify misrepresentations, and develop classifiers to assist platforms like Amazon in detecting and removing falsely advertised products.

Business Case:
The U.S. vitamin and supplement manufacturing industry is valued at $35.6 billion annually, with an expected growth rate of 6.9% between 2021 and 2026.
Vitamins and supplements, classified as food products rather than medicine, are not subject to the strict regulatory standards applied to prescription drugs.
The FDA has limited authority, focusing on post-market enforcement rather than pre-market safety approvals.
Challenges due to lack of oversight:
False advertising and misrepresentation of product efficacy.
Potential health risks for consumers.
Legal and reputational risks for retailers like Amazon selling these products.
Opportunities:
Using analytics to identify and remove misrepresented products, protecting consumer health and legal standing.
Enhancing consumer trust and steering them toward safe, effective products.
Project Deliverables:
Model Development:

Built classification models using consumer reviews of two products:
Skald Fat Burner: 492 reviews (251 misrepresentations, 241 confirming product claims).
Amino Acid Powder: 511 reviews (176 misrepresentations, 335 confirming product claims).
Achieved high classification accuracy:
Cohen’s Kappa for Skald: 0.88
Cohen’s Kappa for Amino Acid Powder: 0.70
Keyword Analysis:

Identified words/phrases that indicate misrepresentation or confirm product claims.
Highlighted differences in keywords across product categories based on their specific claims.
Transfer Learning:

Demonstrated the potential to transfer learning from one supplement type to another with consistent performance across categories.
Data and Tools Used:
Data:
Consumer reviews sourced for two supplement types.
Labels for "misrepresentation" and "confirmation of product claims" verified with high inter-rater reliability.
Tools and Techniques:
Python for model development and analysis.
Natural Language Processing (NLP) for keyword and context analysis.
Statistical methods to measure labeler agreement (e.g., Cohen’s Kappa).
Transfer learning techniques to assess model adaptability across products.
Findings:
Model Performance:
Successfully classified reviews for two supplement types, showcasing adaptability and precision.
Keyword Insights:
Key phrases associated with misrepresentation differ significantly between product categories, reflecting the specific claims made by each supplement.
Transfer Learning Potential:
Models trained on one product type demonstrated reasonable accuracy when applied to another, suggesting broader applicability.
Business Benefits:
Consumer Protection:
Improved consumer knowledge and informed purchasing decisions.
Market Impact:
Reduced sales channels for misrepresented products, impacting bad actors financially.
Legal and Reputational Benefits:
Helped mitigate risks for retailers by ensuring compliance with regulatory standards.
Challenges and Solutions:
Data Labeling Consistency:
Achieved high labeler agreement to ensure reliability of labeled data.
Variability in Product Claims:
Adjusted models to account for differences in product-specific language.
Scalability:
Explored transfer learning to adapt models across multiple product types efficiently.
Conclusion:
This project demonstrates the potential of NLP and machine learning to identify misrepresentations in supplement reviews, paving the way for more robust compliance and consumer protection strategies. Insights gained can be leveraged to enhance transparency, build trust, and create safer markets for dietary supplements.
