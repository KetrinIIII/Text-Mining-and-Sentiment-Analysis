# Text-Mining-and-Sentiment-Analysis

Safe Clinical NLI (P8)

Natural Language Inference (NLI) is a pivotal task in natural language understanding, aiming to ascertain if a statement logically follows from a given premise.

For instance, given the premise: "He returned to the clinic three weeks later and was prescribed antibiotics" an NLI system should deduce that the statement "The patient has an infection" is entailed by the premise.

In recent years, there has been a significant surge in the publication of Clinical Trial Reports (CTRs). As a result, it has become increasingly challenging for clinical practitioners to keep pace with the ever-growing literature to offer personalized evidence-based care. In this context, NLI presents an opportunity to aid in the large-scale interpretation and retrieval of medical evidence.

In this project, we propose to tackle a textual entailment task using clinical trial data. The task is based on a dataset comprising breast cancer CTRs, statements, and labels annotated by domain expert annotators. The annotated statements represent sentences that make a claim about the information within one of the sections in the CTR. The objective is to determine the inference relation (entailment vs. contradiction) between CTR-statement pairs. Additionally, we encourage the exploration of evidence-based retrieval, wherein the NLI system extracts a set of supporting facts from the premise to justify its predictions.
