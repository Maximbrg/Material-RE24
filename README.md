# Temp-Material-RE24

This folder represents the online appendix for the paper "Deriving Domain Models from User Stories: Human vs. Machines", the tree structure of the directory is the following:

--------------------------------------------------
##   Tree Structure
<pre>
├───A Benchmark for Domain Model
│   ├───Agreement
│   │       Agreement - Associations.xlsx
│   │       Agreement - Classes.xlsx
│   │
│   ├───Domain Models
│   │       Gold standard - Associations.xlsx
│   │       Gold standard - Classes.xlsx
│   │
│   └───User Stories
│           camperplus.txt
│           Fish_Chips.txt
│           grocery.txt
│           planningpoker.txt
│           recycling.txt
│           school.txt
│           sports.txt
│           supermarket.txt
│           Ticket.txt
│
├───Discussion
│   ├───False positive error type
│   │       fp-analysis-cohen-kappa.xlsx
│   │       Qualitative Error Analysis.xlsx
│   │
│   └───ML-class-SHAP values
│           1.png
│           2.png
│           3.png
│           4.png
│           5.png
│           6.png
│           7.png
│           8.png
│           9.png
│
├───Domain Model Derivation Approaches
│   ├───ChatGPT
│   │       Prompts.pdf
│   │
│   └───ML
│       ├───Associations
│       │       associations_feature_generator.ipynb
│       │       edges.csv
│       │
│       └───Classes
│               class_feature_generator.ipynb
│
└───Evaluation
    │   Overall results.xlsx
    │
    ├───ChatGPT - outputs
    │   ├───adjusted eval
    │   │       camper_gpt.xlsx
    │   │       chatgpt_recycle.xlsx
    │   │       chatgpt_tickets.xlsx
    │   │       gpt_fish_chips.xlsx
    │   │       gpt_groceries.xlsx
    │   │       gpt_planningpoker.xlsx
    │   │       school_chatgpt.xlsx
    │   │       sports_chatgpt.xlsx
    │   │       Supermarket_chatgpt.xlsx
    │   │
    │   └───gold standard eval
    │           Fish_Chips_output.txt
    │           recycling_output.txt
    │           camperplus_output.txt
    │           planningpoker_output.txt
    │           grocery_output.txt
    │           school_output.txt
    │           sports_output.txt
    │           supermarket_output.txt
    │           Ticket_output.txt
    │
    ├───ML - outputs
    │   ├───adjusted eval
    │   │       associations.xlsx
    │   │       classes.xlsx
    │   │
    │   └───gold standard eval
    │           associations.xlsx
    │
    └───VN-outputs
        └───adjusted eval
                vn_camper_precision.xlsx
                vn_camper_recall.xlsx
                vn_fish_chips_precision.xlsx
                vn_fish_chips_recall.xlsx
                vn_grocery_precision.xlsx
                vn_grocery_recall.xlsx
                vn_poker_recall_precision.xlsx
                vn_recycle_precision.xlsx
                vn_recycle_recall.xlsx
                VN_school_precision.xlsx
                VN_school_recall.xlsx
                VN_sports_precision.xlsx
                VN_sports_recall.xlsx
                VN_supermarket_precision.xlsx
                VN_supermarket_recall.xlsx
                vn_Ticket_precision.xlsx
                vn_Ticket_recall.xlsx
</pre>
