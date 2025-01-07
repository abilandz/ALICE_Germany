# ALICE_Germany
Last update: 20250701-1



Author list consisting of ALICE members affiliated with institutes and universities in Germany.



**Remarks on compilation:**

1. The author list is maintained in the file "DPG_format.tex" and it was compiled using the LaTeX style file "scdpg.cls" provided on DPG 2025 website at the following link https://www.dpg-tagung.de/r25/infoclass.html?language=de

2. In case compilation fails due to lack of support for German language, install locally the following package:

   ```
   sudo apt-get install texlive-lang-german
   ```

3.  Finally, compile with:

   ```
   pdflatex DPG_format.tex
   ```

4. The final list is in the file "DPG_format.pdf"



**Remarks on submission to the DPG website:**

1. Create directly on the DPG website a dummy author list for ALICE Germany Collaboration, merely to obtain the modification key for it (received via email)
2. In the final version of file "DPG_format.tex" inject an \scKey{...} with the key for modifications within curly braces, somewhere within the \begin-\end-block
3. Update on the DPG website the dummy author list with "DPG_format.tex" edited as in Step 2 above
4. For any future update of "DPG_format.tex" follow the same procedure, just modification key will need to be updated



**Other remarks:**

1. The author list of all ALICE members can be generated in LaTeX, pdf and few other formats and exported from this link: https://alice-glance.cern.ch/alice/membership/members/author_list.php
