
# Functional Requirements

1. **RF1.** The application must display the artwork information, including name, artist, dimensions, materials, and price, along with the _Buy_ and _View on Wall_ buttons.
    
2. **RF2.** When pressing _View on Wall_, the application must activate the device’s camera and start scanning the space.
    
3. **RF3.** When starting the AR experience, the application must show two horizontal lines (one aligned with the ceiling and one with the floor) with a message instructing the user to align the wall edges.
    
4. **RF4.** While the user aligns the wall, the application must display a visual indicator showing it is waiting for correct alignment.
    
5. **RF5.** When the lines are correctly aligned, they must change color and remain visible for 3 seconds along with the message “Borders correctly aligned.”
    
6. **RF6.** After alignment, the loading indicator must change to a confirmation indicator and show the message “Make circular movements.”
    
7. **RF7.** During the scan, the application must display the legend “Scanning” along with a cumulative progress indicator.
    
8. **RF8.** At the end of the scan, the progress indicator must be replaced by the message “Scan completed,” visible for 3 seconds.
    
9. **RF9.** Once the scan is complete, the user must be able to place the artwork by tapping the desired area.
    
10. **RF10.** The application must display an arrow pointing to the artwork, a shaded border around it, and an X button to cancel the action.
    
11. **RF11.** If the user taps the artwork, drag mode must be activated, allowing movement only within the scanned space.
    
12. **RF12.** When the artwork is released, it must remain fixed in its new position.
    
13. **RF13.** Once the artwork is placed, the application must display the _Done_ (confirm) and _Buy_ buttons.
    
14. **RF14.** The application must show a numbered walkthrough guiding the user step by step.

---

# Non-Functional Requirements

- **RNF1.** The application must provide clear visual feedback at all stages of scanning and artwork placement.
    
- **RNF2.** Alignment, loading, and confirmation indicators must immediately reflect state changes in the prototype.
    
- **RNF3.** The interface must be intuitive and guide the user step by step without external instructions.
    
- **RNF4.** The application must display consistent interactions throughout all steps of the workflow (scanning, placing, confirmation).
    
- **RNF5.** All messages, icons, colors, and visual elements must maintain consistency in style and meaning within the prototype.
    
- **RNF6.** Simulated actions in the prototype must show immediate changes to reflect user feedback.
    
- **RNF7.** The prototype must represent that the application does not store sensitive data, such as images, camera input, or location.


**Mapping Relationships Between Functional and Non-Functional Requirements**

|**Functional Requirement (RF)**|**Related Non-Functional Requirements (RNF)**|**Relationship Explanation**|
|---|---|---|

|   |   |   |
|---|---|---|
|**RF1** – Display artwork info and buttons|RNF3, RNF4, RNF5|The interface must be intuitive and visually consistent when showing artwork details.|

|   |   |   |
|---|---|---|
|**RF2** – Activate camera and start scanning|RNF1, RNF2, RNF4|Visual feedback and responsive indicators ensure clarity during scanning.|

|   |   |   |
|---|---|---|
|**RF3** – Show horizontal guide lines|RNF1, RNF2, RNF5|Clear and consistent visual elements help users align correctly.|

|   |   |   |
|---|---|---|
|**RF4** – Show waiting indicator for alignment|RNF1, RNF2|Immediate feedback maintains user understanding during the process.|

|   |   |   |
|---|---|---|
|**RF5** – Lines change color when aligned|RNF1, RNF2, RNF5|Color and message consistency ensure the alignment confirmation is clear.|

|   |   |   |
|---|---|---|
|**RF6** – Change to confirmation indicator (“Make circular movements”)|RNF1, RNF2, RNF4|Immediate visual update and consistency in interaction feedback.|

|   |   |   |
|---|---|---|
|**RF7** – Show “Scanning” progress indicator|RNF1, RNF2, RNF6|Clear visual feedback and responsive updates simulate real-time progress.|

|   |   |   |
|---|---|---|
|**RF8** – Show “Scan completed” message|RNF1, RNF2, RNF4|Ensures clear completion feedback and consistent messaging.|

|   |   |   |
|---|---|---|
|**RF9** – Allow user to place artwork|RNF3, RNF4, RNF5|Interface must guide placement intuitively and maintain style consistency.|

|   |   |   |
|---|---|---|
|**RF10** – Display arrow, shaded border, and cancel option|RNF1, RNF3, RNF5|Feedback clarity, intuitive controls, and visual uniformity.|

|   |   |   |
|---|---|---|
|**RF11** – Enable drag mode within scanned space|RNF3, RNF6|Drag actions must respond instantly and intuitively in the prototype.|

|   |   |   |
|---|---|---|
|**RF12** – Artwork remains fixed when released|RNF6|Immediate visual confirmation reflects user action.|

|   |   |   |
|---|---|---|
|**RF13** – Show Done and Buy buttons|RNF3, RNF5|Buttons must be visually consistent and intuitive to understand.|

|   |   |   |
|---|---|---|
|**RF14** – Show numbered walkthrough|RNF3, RNF4, RNF5|Guides users intuitively through steps with consistent style and feedback.|

|   |   |   |
|---|---|---|
|—|**RNF7 (Privacy simulation)**|Applies globally: prototype must not simulate data storage or access.|