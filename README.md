# Navigator-Mapping-Demo-and-Lab
Mapping Controls in ATT&amp;CK Navigator

I have been given the task of validating that measures taken to comply with NIST 800-53 are operational and working as expected.  In this lab exercise, I will map sections of NIST800-53 (AC-2 and SI-4) to MITRE ATT&CK using the ATT&CK Navigator.

Lab Resources Needed:

ATT&CK Control Frameworks Mapping GitHub Repo
ATT&CK Navigator

Part I - Find and Download JSON Layers for AC-2
From the main GitHub repo page, go to the frameworks directory.

2. Choose the nist800-53-r4 directory.

3. Navigate to the layers directory

4. Click on the by_family directory

5. Click on the Access_Control directory

6. Click on AC-2.json

7. Click on the Raw button to be taken to the json file


8. Copy the URL from your browser to use in part II

Part II - Import Mappings
9. In ATT&CK Navigator click on Open Existing Layer

10. Paste the link you copied in part 1 into the space where it says Load from URL

11. Click the arrow next to the link you pasted in


12. Click Yes to Upgrade the layer to ATT&CK v8


13. You should have a resulting mapping set that looks like this.


14. Right-click on any technique and choose select unannotated.


15. Click on the Toggle State button


16. Click on the show/hide disabled button


17. Click on the expand sub-techniques button.


Part III - Scoring with Multiple Controls
17. Repeat steps 1 - 8, this time navigating to the SI-4.json file as shown in the Navigator Mapping Demo lesson.

18. Return to the ATT&CK Navigator and click on the + button to add a new tab


19. Repeat steps 9 - 17 with the link you copied for the SI-4.json in step 18.

20. Click on the + button to add a new tab.

21. Click on Create Layer from other layers.


22. Set the domain to Enterprise ATT&CK v8

Set the score expression to:
(a+(2*b))



23. Click the Create button

