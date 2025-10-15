
# Functional Requirements

RF1. The application must display the artwork information, including name, artist, dimensions, materials, and price, as well as the buttons Buy and View on Wall.

RF2. When pressing the View on Wall button, the application must activate the device’s camera to begin scanning the space.

RF3. When starting the AR experience, the application must show two imaginary horizontal lines (one aligned with the ceiling and the other with the floor) and a message instructing the user to align the top and bottom edges of the wall with the lines on screen.

RF4. While the user aligns the wall, the application must display a visual indicator showing that it is waiting for the correct alignment.

RF5. Once the wall edges are aligned with the guide lines, the lines must change color and remain visible for 3 seconds along with the message “Borders correctly aligned.”

RF6. After confirming the alignment, the loading indicator must change to a confirmation indicator, and the application must display graphical elements showing that the camera is scanning, accompanied by the message “Make circular movements.”

RF7. During the scan, the application must display the legend “Scanning” along with a cumulative progress indicator.

RF8. At the end of the scan, the progress indicator must be replaced by a confirmation indicator along with the legend “Scan completed” for 3 seconds.

RF9. Once the scan is completed, the application must allow the user to place the artwork by tapping on the desired area of the screen.

RF10. The application must display an arrow pointing to the placed artwork, a shaded border around the selection, and an X button to cancel the action if the user wishes to reposition the artwork.

RF11. If the user taps the artwork, a drag mode must be activated that allows moving the artwork only within the scanned space.

RF12. When the artwork is released in a new position, it must remain fixed in that location.

RF13. Once the artwork is placed, the application must display the buttons Done (to confirm the final visualization) and Buy (to purchase the artwork).

RF14. The application must display a numbered walkthrough that guides the user step by step through the required actions.

---

# Non-Functional Requirements

RNF1. The application must provide clear visual feedback during all stages of scanning and artwork placement.

RNF2. The alignment, loading, and confirmation indicators must update immediately when the state changes.

RNF3. The interface must be intuitive and allow the user to easily understand what action to take next.

RNF4. The application must be compatible with supported devices and ensure stability during AR scanning.

RNF5. All messages, indicators, and visual elements must be consistent and easily recognizable.

>Explain easy recognizable meaning. 
