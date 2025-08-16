# 1.Business Understanding

1.1 Background

Academic publications are essential for tracking research productivity, promoting collaboration, and enhancing institutional visibility. However, the challenge of author name ambiguity makes it difficult for universities to accurately identify which publications belong to their faculty members. This is because multiple authors may share the same or similar names, affiliations may be missing or outdated, and authors may change institutions over time.

The University of Zambia (UNZA) needs a reliable and efficient way to identify publications authored by its faculty members across multiple academic databases. This will support accurate reporting of research output, strengthen the institution’s academic profile, and enable better decision-making in research management.

The focus of this project is to develop a Data-driven classification model that can predict whether a given publication belongs to a UNZA faculty member. The system will analyze publication metadata such as author names, affiliations, email domains, co-author networks, and research topics to make this determination.

1.2 Business Objectives

The main objective is to automatically identify publications that belong to UNZA faculty members. This will:
•	Reduce the time and effort required for manual verification of research outputs.
•	Improve the completeness and accuracy of institutional publication records.
•	Enhance research visibility for UNZA by ensuring faculty work is properly credited.
•	Support strategic decision-making in research funding, performance evaluation, and collaborations.

1.3 Business Success Criteria
The success of the project will be measured by:
1.	Classification Accuracy – The automated system should correctly identify at least 80% of publications as belonging or not belonging to UNZA faculty members.
2.	Practical Usability – The system should allow research administrators and other stakeholders to process and verify publications with minimal effort.
3.	Interpretability – The model should provide explanations for its predictions to build trust in the system’s decisions.


1.4 Data Mining Goals

•	Develop a classification model that can predict whether a publication belongs to a UNZA faculty member based on its metadata.
•	Apply supervised machine learning techniques using labeled examples of UNZA and non-UNZA publications.
•	Extract and engineer features such as presence of “University of Zambia” in affiliations, “@unza.zm” in email addresses, and frequent co-authorship with known UNZA staff.
•	Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

1.5 Data Mining Success Criteria
The data mining task will be considered successful if:

• The classification model achieves at least 80% accuracy on a held-out test dataset. 
• Precision and recall are both at least 75%, ensuring both correctness and completeness of UNZA punlication identification. 
• The system can process new, unseen publication data with consistent performance.
