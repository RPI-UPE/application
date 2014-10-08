# RPI-UPE's Application Source

Each semester we must generate a new version of the application with the correct deadline.
The original code for this was created by Amanda Olyha.

## How to use

You should already know how to use LaTeX on your own machine.

1. Update the `UPE_application.tex` file (both the `\UpeDeadline` and `\UpeSemester` variables).
2. Regenerate the `UPE_application.pdf` file using your local LaTeX environment
3. Rename the pdf with this semeseter's season and year (aka Fall2014)
4. Add the pdf to the `old-apps` folder for reasons.
4. Update the website with this new version:
  - remove the old application pdf
  - add the new pdf file to the repository
  - make sure you update the `application.pdf` sym-link
