# ALICE_Germany
Last update: 20251202-1



Author list consisting of ALICE members affiliated with institutes and universities in Germany.



**Compilation:**

1. The author list is maintained in the file "DPG_format.tex" and it was compiled using the LaTeX style file "scdpg.cls" provided on the DPG website at the following link https://www.dpg-tagung.de/r25/infoclass.html?language=de

2. In case compilation fails due to lack of support for German language, install locally the following package:

   ```
   sudo apt-get install texlive-lang-german
   ```

3.  Finally, compile with:

   ```
   pdflatex DPG_format.tex
   ```

4. The final list is in the file "DPG_format.pdf"



**Submission to the DPG website:**

1. Create directly on the DPG website a dummy author list for ALICE Germany Collaboration, merely to obtain the modification key for it (received via email)
2. In the final version of file "DPG_format.tex" inject an \scKey{...} with the key for modifications within curly braces, somewhere within the \begin-\end-block
3. Update on the DPG website the dummy author list with "DPG_format.tex" edited as in Step 2 above
4. For any future update of "DPG_format.tex" follow the same procedure, just modification key will need to be updated



**Previous versions**
Author lists used at the previous DPG meetings are tagged. For instance, to retrieve the version which was used in the DPG 2025 meeting in Cologne, clone this repository locally, and checkout the tag "DPG-2025":

```bash
$ git clone https://github.com/abilandz/ALICE_Germany ALICE_Germany
$ cd ALICE_Germany
$ git checkout "DPG-2025"

# To see the list of all tags in the repository, execute: git tag
```



**Other remarks:**

1. The author list of all ALICE members can be generated in LaTeX, pdf and few other formats and exported from this link: https://alice-glance.cern.ch/alice/membership/members/author_list.php
