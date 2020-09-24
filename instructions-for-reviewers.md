**Dear reviewer**,

Many thanks for participating in the Artefact Evaluation Committee. In the following, we will provide some instructions how to approach the review of an artefact. We also provide an FAQ at ...

# Anonymity

We are in favour of 

# Approach

1. **Most important rule.** If in doubt, check the FAQ or contact the AEC chairs directly. The process is still young and being developed, and we are in fact trying out new things this year.

2. **Become familiar with the ACM classification.** The full text can be found here: https://www.acm.org/publications/policies/artifact-review-badging. It is not always straight-forward to digest, so here is a summary.
    1. Note the differences between repeatability, replicability, and reproducibility.
    2. There are three badges that can be applied: "evaluated", "available", "results validated". These are independent dimensions.
    3. "Evaluated" means that an artefact has undergone the review process successfully. It actually has two sub-levels, and you will be asked to choose between "functional" and "reusable". "Functional" means the bare minimum has been done: the artefact is documented, consistent, complete, and exercisable (code runs and data can be manipulated). "reusable" indicates a significant effort has been made to ascertain reuse and repurposing is facilitated - e.g., community conventions are adhered to **and** the authors provide everything to make it possible to use the dataset in a different context or in a re-analysis of the paper. Note that "evaluated" says nothing about availability - see next.
    4. "Available" is an assessment whether the artefact is permanently available. We will ask you to rate the authors' choice of repository - e.g. a private website is much less likely to be permanently available than a dedicated research store run by a government agency.
    5. "Results validated" refers to the degree to which the results in the paper can be obtained by exercising the artefact by **you** (not the authors of the paper). There are two categories here, "reproduced" and "replicated". You are going to test only for "replication" as you are, of course, using the artefact (and are not trying to obtain the same results in an independent study without it). Note that exact replication of the results is not technically a requirement of this badge: replication within an acceptable tolerance is OK. This allows for cases where analysis methods have a degree of randomness or outside influence that cannot be avoided. We will ask you for your opinion on "within an acceptable tolerance", based on the community's expectations for the given approach in the paper.

3. **Read the paper.** Most artefacts will not make much sense without an understanding of what the paper is trying to achieve and what role the artefact plays in this. You will need to read and understand the paper, but only to the extent required to judge the artefact. All artefacts that you are going to review belong to papers that have already been (conditionally) accepted. You do not need to judge the merits of the paper, your focus is on what it says about reproducibility of the results. For example, if a paper provides only a dataset, you will need to check that the provided data can be used and understood by others to determine whether it supports the findings or not - that would, at the very least, imply availability (short-term? long-term?) and appropriate meta-data (README? CSV headers?). If a paper provides code, you will also need to check whether it works - more on this soon.

4. **Test availability.** Follow the links provided by the authors. Please notify the AEC Chairs **immediately** if an artefact is not completely available. We give the authors a second shot to get it right. We will ask you to rate how difficult it was to obtain the artefact parts.

5. **Think about ethics, licences, safety.** The TPC will have considered the ethical aspects of a paper, but this does not imply that the provided artefact does not exhibit any issues. We will ask you to write a brief statement if you see ethical issues in the release of the data set. We will also ask you to assess whether any licence that comes with it seems fair and non-discriminatory, and whether download and use of an artefact may impact the safety or security of a system or user.

6. **Check the data and meta data.** Check if the data set is well described and whether it fits the description in the paper. Check if the dataset is complete (given the description in the paper). Note any deviations (e.g. number of data points strikingly different, timestamps different etc.)

7. **Try to run the code.** This is the most difficult part. We will ask you to assess how easy or hard it is to get any provided code to run and whether results can be immediately obtain or only with difficulty. Assess the instructions given by the authors and make an honest attempt to get the code to run. If you identify problems that are easy to fix but stand in the way - e.g. hard-coded paths, missing libraries - we ask you to notify the AEC Chairs **immediately but continue with the evaluation**. We will give the authors a second shot to provide a solution. In the meantime, we ask you for a moderate effort to fix the problem (e.g. fix paths, install libraries). We do **not** expect you to spend days or even hours trying to fix broken code - if it doesn't run with minor modifications, then we will not assign a badge. We will provide some more guidelines in the FAQ - and please do feel free to contact us if you are unsure whether you should persist in trying to get code to run.

8. **Try to obtain the results.** The paper authors should provide scripts and documentation how to obtain the results from their code. If this is missing, **please let the AEC Chairs know immediately but continue the evaluation**. We will give the authors a second chance to fix this. As above for running the code, we only expect a reasonable effort from your side: do not spend days trying to figure out how to use the scripts to get the results. But if you can deduce it using your intuition and knowledge of the community standards, please do so.

We hope that these instructions can make your life a bit easier. Let us know if you have further questions. We will publish our answers in the FAQ so they become visible to everyone, too.

Ralph & Matthias
