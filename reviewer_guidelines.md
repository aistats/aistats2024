---
title: Reviewer Guidelines
layout: default
weight: 6
hide: false
---

# AISTATS 2024 Reviewer Guidelines

## How to Review?

The purpose of the review process is twofold. First, to identify papers which offer significant contributions to the fields of artificial intelligence and statistics, for attendees and readers. Second, to provide constructive feedback to authors that they can use to improve their work. Your role as a reviewer is vital to both goals. 

When reviewing a paper, always think about the impact the work may have on the community in the long run: out-of-the-box ideas, novel problems, and "bridging fields" contributions are crucial for the successful development of the field, so do not neglect the importance of papers with this type of contributions. Novel or interdisciplinary works are often very easy to criticize, because, for example, the assumptions they make or the models they use are not yet widely accepted by the community. Yet, such works may be of high importance for the progress of the field in the long run, so please try to be aware of this bias, and avoid dismissive criticism.

_Acknowledgments: The guidelines in this document are partially adopted from the AISTATS 2023 reviewer guidelines, which in turn utilize reviews written for some AISTATS, NeurIPS, ICML, and ICLR papers._

 
## Review Form and Guidelines for Writing a Good Review

The review form will ask you for the following: 

1. **Summary and contributions: Briefly summarize the paper and its
contributions**

    Summarize the paper motivation, key contributions and achievements in a paragraph. Although this part of the review may not provide much new information to authors, it is invaluable to ACs and program chairs, and it can help the authors determine whether there are misunderstandings that need to be addressed in their author response. There are many examples of contributions that warrant publication at AISTATS. These contributions may be theoretical, methodological, algorithmic, empirical, connecting ideas in disparate fields ("bridge papers"), or providing a critical analysis (e.g., principled justifications of why the community is going after the wrong outcome or using the wrong types of approaches.).

2. **Provide 3 keywords about the paper's topic.**

3. **Proivde 3 keywords about your research expertise.**

    The purpose for setting up these 2 questions, together with the "providing 3 keywords" question in the paper submission form, is to allow the AC to evaluate whether the reviewer's expertise matches the submission's research topic. If you notice a discrepancy between your answers to these two questions, this may indicate expertise mismatch, and in this case we suggest you consider putting a lower confidence score in Q16.

4. **Soundness of theory and theorems, if applicable:**

    - Correct
    - Minor errors  (e.g., typo or errors that do not affect the main results)
    - Major errors or trivial results (e.g., an incorrect theorem, or known results)
    - Not applicable

5. **Justification of your provided judgment in Q4, if not applicable, put in "N/A". If your choice is "minor errors" or "major errors", please specify the details of your concerns.**

    These two questions mainly evaluate the paper's soundness in terms of theoretical contributions if applicable. Incorrect claims or methodology are the primary reasons for rejection. Your comments should be detailed, specific, and polite. Please avoid vague, subjective complaints. Thoroughly motivate your criticism so that authors will understand your point of view and potentially respond to you. Remember to provide appropriate references if relevant.

    Example comments:  
    - "Theorem 3.1 contains major errors: the proved convergence rate in line XXX is missing a factor of T^1/3 since [reason for this claim]. Because of this, the correct convergence rate of the proposed algorithm is no better than the baseline method YYY (citation 1)."
    - "Lemma 4.2 contains minor errors: the time complexity figure in line XXX should be O(YYY) instead of O(ZZZ) because [reason for this claim], although this does not affect the final complexity figure too much when combining all algorithmic components together."

    Note that unless the assumptions are very unrealistic and much stronger than those of similar theoretical results in the literature (please justify in detail), otherwise we recommend commenting on the potential issues about assumptions in Q13 additional comments. 

6. **Significance of empirical results, if applicable:**

    - Significant with well supported statistical metrics and appropriate baselines
    - Mixed results (e.g., significant performance in some but not all experiments, missing a baseline)
    - Generally not significant (e.g., overall similar to baselines, missing many baselines)
    - Not applicable 

7. **Justification of your provided judgment in Q6, if not applicable, put in "N/A". If your choice is "mixed results" or "generally not significant", please specify the details of your concerns. (max. 1000 characters)**

    These two questions mainly evaluate the paper's significance in terms of empirical results if applicable. Your comments should be detailed, specific, and polite. Please avoid vague, subjective complaints. Thoroughly motivate your criticism so that authors will understand your point of view and potentially respond to you. Remember to provide appropriate references if relevant.

    Example comments:  
    - "The proposed method outperforms the selected baselines significantly. However, method XXX has not been added to comparison which hinders the significance of the results. Method XXX should be an appropriate baseline to compare with because [describe the reason, e.g., method XXX differs from the proposed method only in aspect YYY]."

8. **Novelty of the theoretical results and/or empirical methodology:**

    - Ground-breaking new results
    - New results that are significantly different from existing ones
    - New results, although incremental and/or combinatorial
    - Known results, or trivial extension of known results 

9. **Justification of your provided judgment in Q8. If your choice is "known results" or "incremental/combinatorial" please specify the previous publication(s) that support your choice.  (max. 1000 characters)**

    Another important axis is the significance and the novelty of the contributions relative to what has been done already in the literature, and here you may want to cite these relevant prior works. Try to find positive aspects, irrespective of your overall (positive or negative) assessment. One measure of the significance of a contribution is (your belief about) the level to which researchers or practitioners will make use of or be influenced by the proposed ideas. Solid, technical papers that explore new territory or point out new directions for research are preferable to papers that advance the state of the art, but only incrementally. Do *not* use criteria such as "the paper's research area is important" or "the paper is well-written" since these aspects are too generic and commonly occur in poor reviews. 

    Example comments:
    - "The proposed method combines training method XXX (citation 1) and sampling method YYY (citation 2) in order to achieve better performance on metric ZZZ. The combination is done by running the sampling step in XXX using sampler YYY, while in the literature the choices of the sampler are usually e.g., AAA (citation 3) and BBB (citation 4). Although combinatorial, this paper is the first one to show that sampler YYY can work in the context of model CCC (citation 5) trained with method XXX."

10. **Non-conventional contributions: does the submission contain non-conventional research contributions? Examples: novel ideas with not widely accepted assumptions, new problems and/or tasks, "bridging fields" contributions.**

    Some submissions may contain out-of-the-box ideas, novel problems, and "bridging fields" contributions are crucial for the successful development of the field, so do not neglect the importance of papers with this type of contributions. If applicable, you can comment on non-conventional aspects regarding the submission's assumptions, model designs and methods, especially if they are not yet widely accepted by the relevant research community.

11. **Clarity: Is the paper clearly written? Consider whether the paper has clearly (1) stated its contributions, notation and results, (2) explained the meaning of the theoretical assumptions, and/or (3) motivated the proposed methodology well with e.g., examples.** 

    Is the submission clearly written? Is it well organized? (If not, please make constructive suggestions for improving its clarity.) Does it adequately inform the reader? (Note that a superbly written paper provides enough information for an expert reader to reproduce its results.)

12. **Relation to prior work: Is it clearly discussed how this work differs from or relates to prior work in the literature? Any related work missing (if yes provide details in Q13)?**

    - All related works are clearly discussed
    - All related works cited but the discussion is less clear
    - Missing some related works (minor)
    - Some important works/baselines missing or described incorrectly

    We recommend you to explain in Q13 whether the submission is written with due scholarship and suitably relates the proposed work to prior work in the literature. The related work section should not just list prior work, but explain how the proposed work differs from, builds upon, and/or improves on it. Note that authors are not expected to know about all non-peer-reviewed work (e.g, preprints such as on arXiv). Other works (whether peer-reviewed or not) that appeared less than 4 months before the submission deadline are considered concurrent to AISTATS submissions; authors are not obligated to make detailed comparisons to such papers (though, especially for the camera ready versions of accepted papers, authors are encouraged to).

13. **Additional Comments: add your additional comments, feedback and suggestions for improvement, as well as any further questions for the authors. what would you do differently if you were given the chance to improve the paper? (Optional)**

    Add here any additional comment you might have about the submission, including questions and suggestions for improvement. Again please avoid vague, subjective complaints. Think about the times when you received an unfair, unjustified, short, or dismissive review. Try not to be that reviewer! Always be constructive and help the authors understand your viewpoint, without being dismissive or using inappropriate language. Remember that you are not reviewing your level of interest in the submission, but its scientific contribution to the field!

14. **Reproducibility. Are there enough details to reproduce the main experimental results of this work?**

    - Sufficient amount of details available for reproducing the main results.
    - Some amount of details available
    - Not enough amount of details available
    - Not applicable: the paper has no experiments

    Please assess whether, with the information provided by the authors in the paper and the supplementary material, the assumptions, experimental settings and limitations of this work are clearly stated. If they are not, consider listing this as a weakness of the paper in the additional comments.

15. **Paper score:**

    1. Reject
    2. Borderline reject
    3. Borderline accept
    4. Accept
    5. Top 10% of accepted papers

    You should NOT assume that you were assigned a representative sample of submissions, nor should you adjust your scores to match the overall conference acceptance rates. The "Overall Score" for each submission should reflect your assessment of the submission's contributions.

16. **Confidence score:**

    1. Educated guess (The submission is not in your area or the submission was difficult to understand. Math/other details were not carefully checked.) 
    2. Somewhat confident (You are willing to defend your assessment, but it is quite likely that you did not understand central parts of the submission or that you are unfamiliar with some pieces of related work. Math/other details were not carefully checked.)
    3. Fairly confident (It is possible that you did not understand some parts of the submission or that you are unfamiliar with some pieces of related work. Math/other details were not carefully checked.)
    4. You are confident in your assessment but not absolutely certain. (It is unlikely, but not impossible, that you did not understand some parts of the submission or that you are unfamiliar with some pieces of related work.)
    5. Absolutely certain (Use this sparingly; please ensure you are very familiar with the related work, you've carefully checked and understood the proofs and/or experimental details if applicable)

    When answering this question, you might want to compare your answers in Q2 & Q3, and consider whether in this particular case you are absolutely certain with your judgment.


17. **Does the submission raise potential ethical concerns? Does this submission raise potential ethical concerns? These include methods, applications or data that create or reinforce unfair biases and/or that have a primary purpose of harm or injury.**

    - No concern
    - Minor concerns
    - Major concerns


18. **Justification of your provided judgment in Q17 about ethical concerns, if not applicable, put in "N/A".**

    Please assess whether the paper discusses the potential negative societal impact and/or ethical issues of the work. If not, please assess if the paper should include this point due to the nature of the research topic or ideas.

    Note that your rating in Q15 should be independent of this ethics assessment. Your duty here is to flag papers that might need additional review from the ethical perspective.

19. **Code of conduct.**

    Agree to abide by the AISTATS code of conduct. The AISTATS code of conduct can be found here: [AISTATS Code of Conduct](http://aistats.org/aistats2024/code-of-conduct.html)

20. **Confidentiality agreement.**

    Reviewers must keep the paper and supplementary materials (including code submissions and LaTeX source), as well as the reviews, confidential. This includes deleting any submitted code at the end of the review cycle to comply with confidentiality requirements.

21. **Confidential comments for the Area Chair (optional).**

    If you have comments that you wish to be kept confidential from the authors, you can use the "Confidential Comments to Area Chair" text field. Such comments might include explicit comparisons of the submission to other submissions, minor formatting issues, and criticisms that are more bluntly stated. If you accidentally find out the identities of the authors, please do not divulge the identities to anyone.


## Best Practices

+ **Be thoughtful.** The paper you are reviewing may have been written by a first
year graduate student who is submitting to a conference for the first time and you
don't want to crush their spirits.

+ **Be fair.** Do not let personal feelings affect your review.

+ **Be useful.** A good review is useful to all parties involved: authors, other
reviewers, and area chairs.

+ **Be specific.** Do not make vague statements in your review, as they are
unfairly difficult for authors to address.

+ **Be flexible.** The authors may address some points you raised in your review
during the discussion period. Make an effort to update your understanding of the
paper when new information is presented, and revise your review to reflect this.

+ **Be timely.** Please respect the deadlines and respond promptly during the
discussion.  If you cannot complete your review on time, please let the Area Chair
know as soon as possible.

If someone pressures you into providing a positive or negative review for a
submission, please notify the Program Chairs right away at
[aistats2024conference@gmail.com](mailto:aistats2024conference@gmail.com).

If you notice unethical or suspect behavior, please notify your Area Chair right
away.


## How to Access and Download Your Assigned Papers

1. Login to the [CMT portal](https://cmt3.research.microsoft.com/AISTATS2024/) using your **reviewer CMT email address**.

2. Select “Reviewer” role by clicking next to “Select Your Role” at the top of the page. You will then see the submissions that are assigned to you in your console. Note that the reviewing process is double-blind, so you will not see author information.

3. Download all your assigned papers by selecting “Actions -> Download Files” in the upper right of the page.


## Other Remarks

1. **Minor formatting issues.** You may find papers with minor formatting issues such as different citation styles. We have decided not to desk-reject these papers and ask you to disregard such minor formatting issues in your reviews (please flag them but do not change your score/evaluation). We will take them into account and ensure the correct style is used if the paper gets accepted.

2. **Supplement.** Some authors forgot to separate the pages for supplementary materials from the main paper, e.g., by splitting the PDF. We are keeping these papers in the review process. If you find such extra pages, you can treat them as supplementary materials. As stated in [the CfP](http://aistats.org/aistats2024/call-for-papers.html), looking at the supplementary materials is optional to evaluate the submission.

3. **Links in submission.** Some submissions may contain links (e.g., URL) to external materials such as code. We wish to emphasize that we cannot guarantee the safety of such external links. Our general recommendation is that you not follow such links and simply take it as a statement from the authors that they are ready to make such material available if the paper is accepted. If you decide to access a link, be aware it might reveal that you have consulted the linked site, and thus potentially reveal that you are involved in the reviewing of the paper. 

4. **Code in Github.** Some of the papers assigned to you may have submitted code. Note that, as for any supplementary material, reviewing such additional information (e.g., code) is optional. When accessing anonymous Github links submitted by authors, please make sure to directly download the code or clone the repository after logging out of your own Github account; please do not fork the repository as this might reveal your identity to the authors. Note also that any submitted code may contain security vulnerabilities.
