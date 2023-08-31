---
title: Submission FAQs
layout: default
weight: 5
---


## Frequently Asked Questions related to AISTATS 2024 submissions


1. **I missed the abstract submission deadline. Can I still submit a full paper?**
No. You must submit the abstract in time for the deadline on Friday October 6th 2023 (AoE).

2. **While submitting a paper, do we need to nominate one of the authors as a reviewer?**
We ask authors to also serve as reviewers in order to ensure that all submissions can receive a sufficient number of reviews whilst ensuring an acceptable load for each reviewer. Due to the recent increase in submissions, we expect we will need a significantly larger number of reviewers than in previous years. Your nominations are important in order to maintain the quality of the conference. There will be a section in the paper submission form to nominate any of the authors to be reviewers. Nominated authors will receive an invitation to be a reviewer, which can be accepted or declined.

3. **We want to submit a version of the work to arXiv. Is it allowed?**
Yes, submission to arXiv is allowed. However, keep anonymity in the AISTATS submission. Do not cite the arXiv paper, for example.

4. **Can we advertise the preprint of my submission on social media?**
We strongly discourage advertising the preprint on social media or in the press while under submission to AISTATS. Under no circumstances should your work be explicitly identified as AISTATS submission at any time during the review period, i.e., from the time you submit the abstract to the communication of the accept/reject decisions.

5. **Can the author list be changed?**
You can change the author list until the deadline of full paper submission (Friday, October 13th 2023 AoE). After this point, only changes to the author order are allowed, but new authors won’t be added.

6. **Can I withdraw my submission?**
Yes. You can withdraw your submission at any point in the reviewing process. For statistical purposes, we will count a submission as “rejected” if it is withdrawn after reviews have been made available to authors.

7. **Can we revise the abstract after the abstract deadline?**
You can revise your abstract before the full paper deadline, but the changes must be minor (e.g., fixing typos or clarify/correct wording). If the contents or length of the abstract is significantly altered, the submission may be desk-rejected.


8. **I am an author as well as a reviewer/area chair, but I can only find my author (or reviewer) role in CMT. What should I do?**
On the CMT page, you will find a “Select Your Role” tab on the top right. If you click on the current role (e.g., Author), you will see a drop down menu showing your other roles, and you can pick the one you need.


9. **Can I use a different email for my CMT reviewer account and TPMS account?**
The easiest approach is to have the same email for your CMT account and the TPMS account. Alternatively, you may use the new “Linked Account” feature of CMT (see “Link to Account” in the dropdown list at the top right of the console), to link your Area Chair/Reviewer CMT account with another CMT account that uses the same email as your TPMS account. Regardless of the chosen path, it will be critical to have CMT and TPMS accounts with matched email addresses.


10. **If our paper is a resubmission from a previous conference, do I have to indicate so in the submission form?**
Yes, authors must specify whether the paper is a resubmission and, if so, they must summarize the main criticisms raised by the previous reviewers and how these have been addressed. This information will be visible to Area Chairs only, but not to reviewers.


11. **Can we submit code/dataset with our submission?**
Yes, and authors are encouraged to do so, as long as anonymity is preserved. For example, you may include your code as part of the supplementary material or through an anonymized link. Please note that papers that promise to release code or dataset (either at submission time or during the rebuttal phase) will be automatically rejected if the authors fail to make the code/dataset public by the camera-ready deadline.


12. **Does the paper need to discuss the method assumptions and limitations?**
It is not compulsory, but authors are nonetheless encouraged to discuss these points, as they will be positively considered during the review phase.


13. **Does the paper need to discuss the societal impact?**
It is not mandatory, but authors are encouraged to discuss the societal implications of their research.


14. **Is there a reproducibility checklist that my paper needs to comply with?**
This year we ask the authors to include a reproducibility checklist in the main paper after references. The checklist does not count towards the 8 page main limit for the submission (or 9 page limit for camera ready). See the submission template (sample_paper.tex in the [AISTATS2024 Paper Pack]({{ site.url }}/aistats2024/AISTATS2024PaperPack.zip)) for the checklist details.

15. **Will my submission be desk-rejected if not including the reproducibility checklist?**
No, but we still strongly suggest the authors include the checklist in submission. If not included, the authors will be asked to submit the checklist during the author feedback period. The checklist is required for the camera ready version of an accepted paper.


16. **Will the questions about industry/academic paper or hardware usage be visible to reviewers or affect the paper decision?**
No, this information will not be visible to reviewers or ACs and will not be taken into account in the paper decisions. It will only be used for statistical purposes.

17. **How can we obtain the citations (references) of our paper in the (Author, Year) format?**
One option to achieve that goal is to use the latex package `natbib`. For that, you may uncomment lines 19-21 and 24 at the beginning of your main TEX file (sample_paper.tex in the [AISTATS2024 Paper Pack]({{ site.url }}/aistats2024/AISTATS2024PaperPack.zip). In other words, you can use the following:

```
% If you use natbib package, activate the following three lines:
\usepackage[round]{natbib}
\renewcommand{\bibname}{References}
\renewcommand{\bibsection}{\subsubsection*{\bibname}}

% If you use BibTeX in apalike style, activate the following line:
\bibliographystyle{apalike}

[...] [YOUR DOCUMENT HERE]

\bibliography{your_bib_file}
```

Note that, when using `natbib`, you can add or remove the parentheses as follows:

```
\cite{foo2021}   % produces Foo et al. (2021)
\citep{foo2021}  % produces (Foo et al., 2021)
```

## Author Response

Authors will be given the opportunity to respond to their reviews before decisions are made. This is to enable them to address misunderstandings, point out parts of their submissions that were overlooked, or disagree with the reviewers’ assessments. In previous years, some authors felt that their responses were ignored. As a reviewer, it is your responsibility to read and (if appropriate) respond to each author’s response. It is not fair to ignore any author response, even for submissions that you think should be rejected. Although it is possible that an author’s response will not change your assessment of a submission, you must convey to the authors that you have carefully considered their comments. As you read each author’s response, keep an open mind. Have you overlooked something? Please update each review to indicate that you have read the author’s response and whether you agree or disagree with it. You should be more specific than “I have read the author’s response and my opinion remains the same.” If that is the case, you should explain why it remains the same, what the author’s response failed to address, etc.

LaTeX files for writing a response to reviewers are available on the AISTATS 2024 homepage ([click here to download the files]({{ site.url }}/aistats2024/AISTATS2024_Author_Response_Pack.zip)). Author responses are due Tuesday, December 5, 2023 (Anywhere on Earth).

