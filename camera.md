--- 
title: Camera Ready 
layout: default 
weight: 7 
hide: false
---


# Instructions for Camera-Ready Paper


Please take some time to read these instructions **in full**. For your camera-ready paper to be included in the proceedings, it is **essential** that you follow the instructions contained on this page.

## TL;DR
* The camera-ready deadline is ~~Friday, March 1st,
2024~~ **Friday, March 8th,
2024, Anywhere on Earth**.
* You have to use the **new LaTeX style file** available at: <https://aistats.org/aistats2024/AISTATS2024CameraReadyPaperPack.zip>
* You have to **upload one PDF file with the de-anonymized paper** (mandatory), **one PDF filled and signed copyright form** (mandatory), and **one URL link to a GitHub repository with code/datasets** (optional).  


Please read the complete details below.

## Deadline


The deadline for the camera-ready submission is ~~Friday, March 1st~~ **Friday, March 8th, 
2024, Anywhere on Earth**. This is a strict deadline; no extensions to the deadline will be granted in any cases. If you miss the deadline, your paper will not be included in the proceedings. We strongly recommend submitting your camera-ready version well in advance of this deadline.


## Submission instructions


You have to upload one PDF file (mandatory), one PDF filled and signed
copyright form (mandatory), and one url link to a GitHub repository with code/datasets (optional).


1) **PDF file (mandatory).** The PDF file must contain the paper, including the
references and acknowledgements, and optionally the textual supplementary
material. **Differently from the initial submission**, now the textual
supplementary material ("the appendix") **must** follow the paper content (after
Acknowledgements and References) in the **same PDF file**. You will also have to
obtain a submission code from the paper style checker by uploading this PDF
file to 
<https://research.engineering.wustl.edu/machinelearning/pub/AISTATS2024/> 
(see [Submission to CMT](#submission-to-cmt) for details). The style
checker has a **10MB file size limit**. **PDFs above 10MB should be reduced**, for example by reducing the pixel density and/or compression rate of included figures in the main text and supplement (The supplement should be included with the main paper in a **single PDF file** when submitting to CMT.)


The PDF file should be named **642.pdf**, with 642 replaced with your submission ID
on CMT.


To prepare your camera-ready PDF paper, please check the following formatting
instructions:


1. Please use the **UPDATED** LaTeX style file available at:
   <https://aistats.org/aistats2024/AISTATS2024CameraReadyPaperPack.zip>.
2. Camera-ready submissions are **limited to 9 pages**, excluding acknowledgements,
   references, and (optionally) textual supplementary material. Please use the
   additional 9th page to address the reviewers’ and meta-reviewer’s feedback,
   which we request you to take into account.
3. The main paper and the textual supplementary material ("Appendix"), if any,
   must now be submitted as a **single PDF** instead of two separate files.
4. Do not change the style file, including spacing. If you have questions about
   the style file or its usage, please contact the 
   [Publications Chair](https://aistats.org/aistats2024/committee.html).
5. Your paper must use **US letter** format (default in the style file). Do 
   **not** change this to A4 paper format.
6. You must use the fonts as defined in the style file. In addition, please **avoid using Type 3 fonts** anywhere in your document, including in embedded images. See <https://www.ics.uci.edu/~chenli/pdf-font-types/index.html> for more information.
7. Please use **ALL CAPS section headings**, as detailed in the LaTeX templates.
8. Citations **must** be in the **“(Author, Year)” format**, e.g., (Cheesman, 1985). To
   achieve that, you may use the `natbib` LaTeX package (or any other similar one
   that achieves the same purpose). Be sure that the sentence reads correctly
   if the citation is deleted; e.g., instead of “As described by (Cheesman,
   1985), we first frobulate the widgets,” write “As described by Cheesman
   (1985), we first frobulate the widgets.”
9. The paper must be **de-anonymized**, i.e., the author names and institutions
    should be visible. For that, please make sure to use
    `\usepackage[accepted]{aistats2024}` when loading the style file.
10. The acknowledgements section should be titled "Acknowledgments".
    Acknowledgements are optional, but if your paper contains this section, it
    must appear before the References.
11. The reference section should be titled "References". The references listed
    at the end of the paper can follow any style as long as it is used
    consistently.
12. The reproducibility checklist should be placed after the "References" section and titled "Checklist".
13. Please consider the following colorblind-friendly guidelines for
    introducing color in your figures and plots:
    <https://usabilla.com/blog/how-to-design-for-color-blindness>.
14. Further formatting instructions can be found in the `sample_paper.pdf` file
    available at
    <http://aistats.org/aistats2024/AISTATS2024CameraReadyPaperPack.zip>.


2) **Copyright form (mandatory)**. Please download the PMLR copyright form,
available at <http://proceedings.mlr.press/pmlr-license-agreement.pdf>, fill it
in, sign it, rename it as **642-Permission.pdf** (with 642 replaced by your
submission ID on CMT), and submit it with the rest of the documents. It is
sufficient for one author to sign the agreement on behalf of all authors.


3) **Code/Dasets (optional)**. To include **code/datasets** you can provide the public 
  URL where the code can be found in
  the appropriate field of CMT submission form.  **If you promised to release
  code/datasets** (either in the original submission PDF or during the rebuttal),
  **the code/dataset must be released**. In this case, the AISTATS Chairs will
  check the availability of the code/dataset and, if it isn’t available by the
  camera-ready deadline, your submission may be excluded from the conference
  proceedings.
* If you wish to include any **videos**, provide the
  public URL where the video is available in the appropriate field of the CMT
  submission form. **NOTE**: This does not refer to the recorded presentation
  explaining your paper, which will be submitted/recorded separately, but to any other videos containing, e.g., experimental results.


## How to avoid the most common formatting violations


* Please make sure any textual supplementary material ("the appendix") is
  submitted in the same file as the main paper.
* Your paper must **not exceed 9 pages**, except for acknowledgements, references,
  and (optionally) textual supplementary material.
* Your paper must be in **US letter size** (i.e., not A4 or other sizes).
* You must use the fonts as defined in the style file.
* Please ensure that your camera-ready submission contains author information
  (names and affiliations), instead of "Anonymous Author N" as was required for
  the original submission, and that the submitted list of authors and the
  ordering among them **matches the information on CMT**.


## Submission to CMT

Camera-ready submissions must be submitted via CMT:
<https://cmt3.research.microsoft.com/AISTATS2024>. If you are also a reviewer or
Area Chair, make sure that your role is set to “Author”. To change your role to
“Author,” click next to “Select Your Role” in the top right of the page.

In the CMT Author Console there is now a new link to "Create camera-ready
submission" for each accepted paper. Use this link to submit camera-ready
papers. The CMT form will ask you for the title, the abstract, the list of
authors (only changes to the author order are allowed at this point, as per the
submission agreement), and the following files (where 642 is to be replaced by
your submission ID): **642.pdf** and **642-Permission.pdf**.

Please ensure that the submitted **title and abstract match the ones in the
camera-ready version**, and do not include any LaTeX commands or other
non-human-readable markup.

The final version will appear in the [PMLR proceedings](https://proceedings.mlr.press/), published by JMLR W&CP. The CMT will ask you to agree to have your work published by JMLR according to the agreement outlined [here](http://proceedings.mlr.press/pmlr-license-agreement.pdf).

You will also be asked to provide **a submission code obtained by an automated
style checker**. To obtain the code, please follow these steps: 

1. Go to
   <https://research.engineering.wustl.edu/machinelearning/pub/AISTATS2024/> 
2. Provide the paper ID (from CMT), your name (just one author), your e-mail
   and the submission PDF file. If the paper passes the style checks, you will
obtain a submission code. (Please ignore the warnings of the style checker.)
**The submission code is only valid for this particular PDF file**. If you
further edit the PDF, you will need to obtain another submission code.  
3. When submitting your paper on CMT,  you need to provide the style checker
   submission code.
4. The style checker has a **10MB file size limit**. **PDFs above 10MB should be reduced**, for example by reducing the pixel density and/or compression rate of included figures in the main text and supplement.

You may continue to edit your camera-ready submissions until the camera-ready
deadline.

We thank [Roman Garnett](https://www.cse.wustl.edu/~garnett/) for kindly
helping the AISTATS Chairs to set up and host the paper style checker. 



## Instructions for Posters and Recorded Presentations

Instructions will be updated shortly.




<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


## Instructions for Posters

**deadline: March 14th, 2024 AoE** 

To see the full instructions, visit [the wiki](https://wiki.eventhosts.cc/en/reference/posteruploads).

Your paper will be presented in a virtual format on GatherTown and on the live virtual
site. You should prepare **two graphics** for your paper by March 14th AoE (anywhere
on Earth):

- A PNG of your **poster** in landscape format (recommended 16:9 aspect ratio). The
maximum dimensions of a poster are 5120 x 2880 pixels and no more than 10 MB.

- A PNG **thumbnail** (recommended 5:4 aspect ratio) that represents your poster.
Typically this thumbnail is a single figure from your paper (but it could be
anything that represents your paper). The maximum dimensions of thumbnails are
320 x 256 pixels and no more than 5 MB.

The Poster Upload page has an option, *Scale images to fit*, which will scale
your upload so that it fits within the limits (exceptionally large images cannot
be scaled). Using this option will allow images that are larger to be uploaded
and rescaled as they are uploaded.

Use a solid background for your posters and thumbnails as opposed to transparent.
This works better in the virtual poster spaces.

To submit your poster, follow the [submission link](https://virtual.aistats.org/PosterUpload).
If you don't see your paper listed on the page, try logging in using the
**same email address** that you used on CMT.


## Instructions for Recorded Presentations

**deadline: March 14th, 2024 AoE** 

You will also pre-record a video presentation. 

Papers accepted as **Oral will record a 12-minute video** 
and papers accepted as **Poster will record a 5-minutes
video**. SlidesLive will be sending you an email directly from slideslive.com
with further instructions on how to record and upload your video. Please
whitelist `slideslive.com` in your spam filter and coordinate with your
co-authors on recording and uploading your video. The deadline for uploading
this video is March 14th AoE (anywhere on Earth).

 -->
