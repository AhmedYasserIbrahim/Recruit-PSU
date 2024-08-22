# Description

Due to the limitations of the Softr platform, which does not support direct updates to Google Sheets data, we implemented two automated workflows as an alternative solution using Make Academy.

Each workflow is designed to streamline the data management process by leveraging the input gathered from forms filled out on the Recruit PSU platform. When a user submits a form, the automation scenario takes that submission as its input. The system then searches for the corresponding row in the Google Sheets document that needs to be updated. Once the correct row is identified, it populates the relevant fields with the new data provided by the user.

After successfully updating the data, the workflow sends a confirmation email to the user, notifying them of the successful update. This ensures clear communication and enhances the user experience.

For reference and further understanding, the scenario JSON files, which outline the automation procedures, are attached to this repository. Additionally, you can find screenshots of the automation scenarios that illustrate the setup and flow of the processes.
