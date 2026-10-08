# Cell-Cell-communication

**Proposed IL6–IL6R Signaling in Immune Cell Communication**

**Biological Question**
How does IL6 signaling through IL6R help plasma cells survive and carry out their role in the immune response?

## Chosen sender cell and biological context

| **Item** | **Answer** |
|----------|------------|
| **Sender cell** | Plasma cell |
| **Biological context** | Immune signaling and cell-to-cell communication through the IL6–IL6R pathway |
| **Main purpose** | May help regulate immune responses, inflammation, cell survival, and communication between immune and target cells |

## Candidate Ligand and Evidence for Sender-Cell Expression

| **Item** | **Information** |
|----------|----------------|
| **Sender Cell** | Plasma cell |
| **Candidate Gene** | **IL6** |
| **Protein Name** | Interleukin-6 (IL-6) |
| **Expression Evidence** | Plasma cells can produce and secrete IL-6, a cytokine involved in immune signaling and regulation of immune responses. The Human Protein Atlas classifies IL-6 as a secreted protein with expression in immune-related cells and tissues, supporting its role as a signaling molecule released by plasma cells. |
| **Source** | https://www.proteinatlas.org/ENSG00000136244-IL6 |

## Receptor and Receiver Cell with Supporting Evidence

| **Component** | **Answer** |
|--------------|------------|
| **Ligand** | IL6 (Interleukin-6) |
| **Receptor** | IL6R (Interleukin-6 Receptor) |
| **Receiver Cell** | Neutrophil |
| **Signaling Context** | Inflammatory immune response |
| **Supporting Evidence** | IL-6 exerts its biological effects by binding to the IL6R receptor complex on target cells. Neutrophils express IL6R and respond to IL-6 signaling, which regulates immune activation, inflammation, and recruitment of immune cells during inflammatory responses. |
| **Supporting Source (OmniPath)** | https://explore.omnipathdb.org/search?q=IL-6%2C&tab=intercell&species=9606,https://explore.omnipathdb.org/search?q=IL6R%2C&tab=intercell&species=9606&parents=receptor |
| **Supporting Source (Human Protein Atlas)** | https://www.proteinatlas.org/ENSG00000160712-IL6R |

## OmniPath Evidence

| **Component** | **Gene** | **Role** |
|--------------|----------|----------|
| IL6 | IL6 | Ligand (secreted signaling molecule) |
| IL6R | IL6R | Receptor |

## STRING Network Image and Interpretation

| **STRING Result** | **Value** |
|------------------|-----------|
| **Number of Proteins** | 11 |
| **Observed Edges** | 50 |
| **Expected Edges** | 37 |
| **PPI Enrichment p-value** | 0.0193 |
| **Average Node Degree** | 9.09 |
| **Local Clustering Coefficient** | 0.931 |

### Interpretation

The STRING network shows that the 11 proteins are highly connected with each other. There are 50 observed interactions, which is more than the 37 interactions expected by chance. The PPI enrichment p-value (0.0193) suggests that these proteins are biologically related and likely work together in the same pathways.

The average node degree of 9.09 means that each protein interacts with about nine other proteins on average. The local clustering coefficient of 0.931 indicates that the proteins form a closely connected group. Overall, the results suggest that these proteins are involved in common biological functions, particularly those related to IL6 signaling and immune responses.

## STRING Network Image and Interpretation

<img width="389" height="208" alt="image" src="https://github.com/user-attachments/assets/aa232237-7335-40bc-b778-393188dd00a8" />

The STRING network contains 11 proteins connected by 50 observed edges, which is higher than the 37 edges expected by chance. The PPI enrichment p-value (0.0193) indicates that the proteins are significantly more interconnected than expected, suggesting that they participate in related biological processes involved in IL6–IL6R signaling. 

## STRING Network Image and Interpretation

| **STRING Result** | **Value** |
|------------------|-----------|
| **Number of Proteins** | 11 |
| **Observed Edges** | 50 |
| **Expected Edges** | 37 |
| **PPI Enrichment p-value** | 0.0193 |
| **Average Node Degree** | 9.09 |
| **Local Clustering Coefficient** | 0.931 |

### Interpretation

The STRING network shows that the 11 proteins are highly connected with each other. There are **50 observed interactions**, which is more than the **37 interactions expected** by chance. The **PPI enrichment p-value (0.0193)** suggests that these proteins are biologically related and likely work together in the same pathways.

| **Item** | **Information** |
|----------|----------------|
| **Enriched Process** | Cellular response to interleukin-6, cytokine receptor binding, interleukin-6 receptor binding, immune response, and regulation of inflammatory signaling |
| **STRING Evidence** | 11 proteins; 50 observed edges; 37 expected edges; PPI enrichment p-value = 0.0193 |
| **Protein 1** | **IL6R** – Receptor for IL6 that initiates IL-6 signaling when the ligand binds. |
| **Protein 2** | **IL6** – Cytokine ligand that binds to IL6R and triggers downstream signaling. |
| **Protein 3** | **IL6ST (gp130)** – Signal-transducing receptor subunit required for IL-6 signaling. |
| **Protein 4** | **STAT3** – Transcription factor activated downstream of IL6R that regulates gene expression. |
| **Protein 5** | **JAK2** – Kinase that phosphorylates and activates STAT3 during IL-6 signaling. |

## InAct Validation

| **Item** | **Information** |
|----------|----------------|
| **Protein Pair** | IL6 – IL6R |
| **IntAct Record** | EBI-9007446 |
| **Interaction Type** | Physical association |
| **Experimental Detection Method** | Pull-down assay |
| **Organism** | *Homo sapiens* (human) |
| **Host Organism** | In vitro |
| **Positive Interaction** | Yes |
| **Publication** | Li H., Wang H., Nicholas J. (2001). *Detection of direct binding of human herpesvirus 8-encoded interleukin-6 (vIL-6) to both gp130 and IL-6 receptor (IL-6R) and identification of amino acid residues of vIL-6 important for IL-6R-dependent and -independent signaling.* |
| **Journal** | *Journal of Virology (J. Virol.)* |
| **Publication Reference** | PMID: 11238588 |
| **Evidence Conclusion** | The IntAct record provides experimental evidence from a pull-down assay showing a positive physical association between IL6 and IL6R. This supports the proposed IL6 → IL6R signaling pathway involved in cytokine-mediated cell-to-cell communication. |

I chose IL6 and IL6R because they are the ligand and receptor in the proposed IL-6 signaling pathway. IntAct contains a curated interaction record (EBI-9007446) for this protein pair. The interaction was detected through a pull-down assay performed under in vitro conditions. IntAct reports the interaction as a positive physical association, providing experimental evidence that IL6 interacts with IL6R. This finding supports the proposed IL6 → IL6R signaling pathway and its role in cytokine-mediated cell-to-cell communication. Since IntAct already provides experimental evidence for this protein pair, examining another protein pair is not necessary.

## Final model and 150-2500 word interpretation

<img width="209" height="149" alt="image" src="https://github.com/user-attachments/assets/7da5f9be-0af5-44d4-9e91-2b696304d4e3" />

  This proposed model suggests that IL6 signaling may play an important role in communication between plasma cells and other immune cells. IL6 acts as the signaling molecule, while IL6R and IL6ST (gp130) receive and transmit the signal inside the target cell. The proteins identified in the STRING network, such as JAK1, JAK2, and STAT3, are connected to this pathway and help carry the signal from the cell surface to the nucleus. As a result, the pathway can influence processes related to immune regulation, inflammation, and cell survival.

  Several databases provide evidence that supports this model. OmniPath identified the IL6–IL6R interaction, while STRING showed that IL6R is closely associated with proteins involved in cytokine signaling. IntAct also reported a positive interaction between IL6 and IL6R based on experimental data. Although these results support the existence of the IL6 signaling pathway, they do not prove every step of the pathway in a specific biological setting. More laboratory studies would be needed to confirm how this signaling system functions in plasma cells and its exact effects on cellular responses.

## Questions and Answers

**1. What sender cell did you choose, and in what tissue or biological context does it act?**

I chose the plasma cell as the sender cell. Plasma cells are specialized B cells that are found mainly in the bone marrow, lymph nodes, and other lymphoid tissues. They play an important role in the immune system by producing antibodies and signaling molecules involved in immune responses.

**2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?**

The signaling molecule I identified is Interleukin-6 (IL6). Evidence from OmniPath identified IL6 as the ligand in the signaling pathway. IL6 is a well-known cytokine that can be produced by immune cells and is involved in communication between cells during immune and inflammatory responses.

**3. What receptor receives the signal, and which receiver cell did you select?**

The receptor that receives the signal is IL6R (Interleukin-6 receptor). The receiver cell I selected is a B cell, which can respond to IL6 signaling through IL6R and related signaling proteins.

**4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact dependent?**

This pathway mainly represents paracrine signaling because IL6 is released by one cell and acts on nearby cells that express IL6R. In some situations, IL6 can also function through autocrine signaling, but paracrine signaling best describes the proposed model.

**5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.**

The most relevant proteins are IL6ST (gp130), JAK1, JAK2, STAT3, and IL6. IL6 binds to IL6R, while IL6ST forms the signaling receptor complex. JAK1 and JAK2 transmit the signal inside the cell, and STAT3 acts as a transcription factor that regulates gene expression in response to IL6 signaling.

**6. What enriched pathway or biological process is consistent with your proposed mechanism?**

One enriched biological process identified in STRING is the cellular response to interleukin-6. Other related processes include cytokine receptor binding, interleukin-6 receptor binding, and regulation of immune and inflammatory responses. These processes are consistent with the proposed IL6–IL6R signaling pathway.

**7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?**

IntAct showed a curated interaction between IL6 and IL6R (Record: EBI-9007446). The interaction was reported as a positive physical association and was detected using a pull-down assay under in vitro conditions. This provides experimental evidence that IL6 interacts with IL6R.

**8. Which parts of your final model are strongly supported, and which parts remain an inference?**

The interaction between IL6 and IL6R is strongly supported because it is documented in OmniPath, STRING, and IntAct. The involvement of IL6ST, JAK1, JAK2, and STAT3 is also supported by known signaling relationships and STRING network associations. However, the exact downstream cellular response in the selected receiver cell remains an inference because it was predicted from pathway information rather than directly tested in this activity.
**9. What cellular response is expected in the receiver cell, and why?**

The expected cellular response is the activation of immune and inflammatory signaling pathways, leading to changes in gene expression through STAT3 activation. This occurs because IL6 binding to IL6R activates downstream signaling proteins that regulate genes involved in immune responses, cell survival, and inflammation.

## References and database links

**HPA:** https://www.proteinatlas.org/ENSG00000160712-IL6R

**OmniPath:** https://explore.omnipathdb.org/search?q=IL-6%2C&tab=intercell&species=9606

**STRING:** https://string-db.org/cgi/network?taskId=bqA4beNb55rG&sessionId=bBOZvtAZPsKA

**IntAct:** https://www.ebi.ac.uk/intact/details/interaction/EBI-9007446

