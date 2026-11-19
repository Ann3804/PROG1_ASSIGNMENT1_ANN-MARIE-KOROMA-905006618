# PROG1_ASSIGNMENT1_ANN-MARIE-KOROMA-905006618
WASTE MANAGEMENT

## Pseudocode

START 
    DECLARE location AS String
    DECLARE wasteType AS String
    DECLARE severity AS String
    DECLARE priority AS String
    DECLARE again AS String

    OUTPUT "Welcome to Simple Waste Priority Checker"

    DO
        OUTPUT "Enter Location:"
        INPUT location

        OUTPUT "Enter Waste Type"
        OUTPUT "(Plastic / Organic / Blocked Drain / Hazardous):"
        INPUT wasteType

        OUTPUT "Enter Severity (Low / Medium / High):"
        INPUT severity

        IF wasteType = "Blocked Drain" OR wasteType = "Hazardous" THEN
            priority ← "HIGH"
        ELSE
            IF severity = "High" THEN
                priority ← "HIGH"
            ELSE
                priority ← "NORMAL"
            END IF
        END IF

        OUTPUT "Location: " + location
        OUTPUT "Waste Type: " + wasteType
        OUTPUT "Priority: " + priority

        IF priority = "HIGH" THEN
            OUTPUT "URGENT! Clean this drain immediately"
        ELSE
            OUTPUT "This will be collected soon"
        END IF

        OUTPUT "Do you want to report again? (YES/NO)"
        INPUT again

    WHILE again = "YES"

    OUTPUT "Thank you for helping keep Freetown clean"
END
## FLOWCHART
flowchart<img width="785" height="1600" alt="ANN FLOW" src="https://github.com/user-attachments/assets/1b102011-b204-4310-ad4f-413bfb20902b" />
## 
[ANN ASSIGNMENT.pdf](https://github.com/user-attachments/files/35089216/ANN.ASSIGNMENT.pdf)                         [ANN.docx](https://github.com/user-attachments/files/35089412/ANN.docx)




