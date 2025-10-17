
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
