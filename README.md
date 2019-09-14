# NIH All of Us Participant Consent REDCap Project Data Dictionary

A REDCap data dictionary CSV is a serialized snapshot of your REDCap project's data collection instruments. It does not contain any actual data.

This particular REDCap project is designed for capturing participant consent for the NIH *All of Us* research program. 

[Read more about the *All of Us* research program.](https://www.nih.gov/research-training/allofus-research-program)

[Read more about REDCap.](https://www.project-redcap.org/
)

## How to Use

There are two versions:

* One with dynamic SQL fields (the filename contains `_with_sql`)
* One without any SQL fields

You typically will need administrative privileges in order to upload the dynamic-SQL version to REDCap.

In your REDCap project, go to the *Project Setup* screen.

Down in the *Design your data collection instruments* box, click the `Data Dictionary` button. 

You'll be taken to the *Data Dictionary* screen. Scroll down to the *Upload your Data Dictionary file* box.

![](https://raw.githubusercontent.com/wcmc-research-informatics/nih-pmi-data-dictionary/master/docs/upload-your-data-dictionary.png)

## Release Notes

April 13, 2018

- "Today" buttons that were adjacent to DOB fields have been hidden from the UI
- Compensation Signature Date field has been hidden from the UI 
- Other minor changes

March 15, 2018

- New Compensation Signature form added with signature field and date
- Age calculation formula fixed so that age calculates correctly when date is exactly 18 years ago
- New fields added to Community Recruitment Survey
- Other minor changes

February 8, 2018

- Two versions are now available: one with dynamic SQL fields and one without.
- Added fields for Epic-sourced phone and email.
- Added a calculated field for current age.
- Added a Participant Withdrawal form.


