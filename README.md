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

![image](https://github.com/user-attachments/assets/a1434297-a0e9-4701-8cf5-ad5cc313ab40)


8. Copy the URL from your browser to use in part II

Part II - Import Mappings
9. In ATT&CK Navigator click on Open Existing Layer

10. Paste the link you copied in part 1 into the space where it says Load from URL

11. Click the arrow next to the link you pasted in

![image](https://github.com/user-attachments/assets/5ea06a7b-de09-45b7-839c-872972a8266f)


12. Click Yes to Upgrade the layer to ATT&CK v8

![image](https://github.com/user-attachments/assets/071a3b6f-e3a0-4398-8d53-3cd52a41ae79)


13. You should have a resulting mapping set that looks like this.

![image](https://github.com/user-attachments/assets/303709a4-4fd6-4ba2-82fa-39c34540ac1a)


14. Right-click on any technique and choose select unannotated.

![image](https://github.com/user-attachments/assets/02f2f140-fdaa-4422-8de5-39f888a4682f)


15. Click on the Toggle State button

![image](https://github.com/user-attachments/assets/b7a0297e-a863-4375-891f-e5e1f2071463)


16. Click on the show/hide disabled button

![image](https://github.com/user-attachments/assets/2f01297c-8b68-4a96-96a2-b8598b968889)


17. Click on the expand sub-techniques button.

![image](https://github.com/user-attachments/assets/120f4377-d214-4c5f-977b-1e1c86d84b26)


Part III - Scoring with Multiple Controls
17. Repeat steps 1 - 8, this time navigating to the SI-4.json file as shown in the Navigator Mapping Demo lesson.

18. Return to the ATT&CK Navigator and click on the + button to add a new tab

![image](https://github.com/user-attachments/assets/27a98340-c4bc-4654-a1b8-f8d87b9730a6)


19. Repeat steps 9 - 17 with the link you copied for the SI-4.json in step 18.

20. Click on the + button to add a new tab.

21. Click on Create Layer from other layers.

![image](https://github.com/user-attachments/assets/6f8bd35e-7786-42ee-abe6-7ed1e6d84943)


22. Set the domain to Enterprise ATT&CK v8

Set the score expression to:
(a+(2*b))

![image](https://github.com/user-attachments/assets/98c473ff-9625-406d-8df1-fe3ac19c53c8)


23. Click the Create button

