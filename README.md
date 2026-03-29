Zero-Shot Text-to-SQL using Transformer Models
Overview

This project evaluates the ability of transformer-based models to generate SQL queries from natural language using zero-shot prompting.

Objective

To compare model performance in zero-shot Text-to-SQL tasks.

Models

Flan-T5
Falcon

Dataset

Spider dataset (50 samples)

Method

Zero-shot prompting
No fine-tuning

Metrics

Exact Match
Soft Match
Execution Validity

Results

Model	      Exact Match	  Soft Match	  Execution Validity
Flan-T5	    0%	          100%	        20%
Falcon	    0%	          100%	        98%

Key Insights

Both models understand query intent (100% soft match)
Falcon produces far more executable SQL queries
Execution validity is the most reliable metric

Conclusion

Falcon significantly outperforms Flan-T5 in zero-shot SQL generation, making it more suitable for real-world applications.

Files

Zero_Shot_Text_to_SQL_Generation .ipynb
final_results_real.csv

Author

Shahrokh Ahmadinasab Omran
