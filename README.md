**User story**

As a data catalogue user, I want to download the data dictionary so I can work with it in my preferred tools.
As a data catalogue editor, I want to be able to download the existing data dictionary so that I can make changes in the software of my choice, then upload the changes using the existing import feature.

**Additional context**

This feature should build on features that exist already. We have features already that can import and export csv and excel.

Search results can be downloaded as .csv #22
Allow import of Excel (.xslx) files to populate the data dictionary #115
The data dictionary is in the entity reference to a paragraph , see field_columns on content type data_set. The label for dataset is Metadata record

**Proposed solution**

Developer to determine the details.
On the import columns build page, /node/nid/add-columns, there should be an option to download the data dictionary as csv. This should be conditional, if there are no data columns, there should be no download option.
On the node view, there are links to download either a csv or and excel copy of the data dictionary. This should be conditional, if there are no data columns, there should be no download option.

**Screenshots**

Download links as they display on the node view
![screenshot](https://private-user-images.githubusercontent.com/3910508/271006686-b79c86e5-0433-4655-a81b-763fb0790928.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDI1NjY0NTgsIm5iZiI6MTcwMjU2NjE1OCwicGF0aCI6Ii8zOTEwNTA4LzI3MTAwNjY4Ni1iNzljODZlNS0wNDMzLTQ2NTUtYTgxYi03NjNmYjA3OTA5MjgucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQUlXTkpZQVg0Q1NWRUg1M0ElMkYyMDIzMTIxNCUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyMzEyMTRUMTUwMjM4WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NjYwYzE0YWZjNzc3ZTViNjkxMjJlYmQ5Y2ZhM2U1YjI3ODkxMzhiZTc4YTEzZjZkYzM5OTAzMmVjZmNkM2E0MyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.Du1nRexv_3vJCYW4o09zKtUdss0VeF-3YsDpcbZn16U)
