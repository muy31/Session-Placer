# Session-Placer
A notebook I created to demonstrate one way to assign students, participants, or attendees to scheduled sessions by preference and without going over max session capacity. Created for implementation by Yale Africa Innovation Sympoisum (https://www.yaleafricainnovation.org/). 

### How to run:
1. Make sure all the innovation lab data and their schedules, are uploaded in the format shown in "Example Workshop List.
2. Likewise, make sure all the student preference data is uploaded in the format shown in "Example Students List". This can be done auto-magically through a Google Form!
3. For now, **keep STUDENTS_MUST_ATTEND_ALL_SESSIONS variable to False.** Muyi will implement the True aspect later if necessary (not hard, but hopefully unnecessary).
4. For all the other constants in CAPS (*code section 2*) , edit parameter values as necessary. Descriptions to what each variable means are commented next to them.
5. **Hit 'Runtime' at the top and navigate to 'Restart and Run All'. Connect to Google Drive when pop up comes.**
6. Scroll down and enjoy! You can play with the output, it makes tables sometimes. The schedule for each student is created at the bottom and **automatically saved to "Crafted Schedule"** (another sheet in this folder). After making a schedule, **make sure to download it or make a copy if you intend on using it** before running this script again!
