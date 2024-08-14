# Quick Start Guide: Setting Up jBPM for Kibo Fulfillment Workflows

This Quick Start Guide will help you set up jBPM Business Central on your local system, specifically for working with the Kibo Fulfillment Workflows project. Whether you're new to jBPM or setting up for a quick demo, this guide will walk you through each step to get you up and running smoothly.

## Prerequisites

Before you begin, make sure you have the following:

- A Mac computer
- Basic understanding of terminal commands
- Internet access to download necessary files

## Step 1: Download and Install jBPM

1. Visit the [jBPM website](https://www.jbpm.org/).
2. Download the latest stable version of jBPM (7.74.1.Final) for Mac.
3. Once the download is complete, unzip the downloaded file to a convenient location on your system.

## Step 2: Start jBPM Business Central

1. Open your terminal.
2. Navigate to the unzipped jBPM folder.
3. Run the following command to start the jBPM server:
    ```bash
    jbpm-server/bin/standalone.sh
    ```
4. Wait for the server to fully start. You’ll know it’s ready when you see a message indicating that the server is listening on port 8080.
5. Open your web browser and go to:
    ```
    http://localhost:8080/business-central
    ```

## Step 3: Log In to Business Central

1. In your browser, log in using the default credentials:
    - **Username:** `wbadmin`
    - **Password:** `wbadmin`
2. After logging in, you’ll have access to the jBPM Business Central dashboard, where you can start working with your projects.

## Step 4: Clone the Kibo Fulfillment Workflows Project

1. Open a new terminal window.
2. Navigate to the directory where you want to store the project.
3. Run the following git command to clone the Kibo Fulfillment Workflows project:
    ```bash
    git clone https://github.com/KiboSoftware/kibo-fulfillment-workflows.git
    ```
4. The project will be downloaded to your local machine, setting the stage for importing it into jBPM Business Central.

## Step 5: Import the Kibo Fulfillment Workflows Project into Business Central

1. In the jBPM Business Central dashboard, navigate to **Menu > Design > Projects**.
2. Click on the **Add Project** button located on the right side of the screen.
3. Select **Import Project** from the dropdown menu.
4. In the **Repository URL** field, enter the filesystem location where you cloned the repository, using the following format:
    ```
    file:///{filesystem_location_of_cloned_repository}
    ```
    - For example:
    ```
    file:///Users/your_username/projects/kibo-fulfillment-workflows
    ```
5. Click **Import** to load the project into Business Central.
6. Select the project that appears to confirm the import.
7. Click **Ok** to complete the process.

## Step 6: Review and Work with the Kibo Fulfillment Workflows

With the project successfully imported, navigate through the Kibo Fulfillment Workflows project. You can now review, modify, and manage business assets such as processes, forms, rules, decision tables, and more, directly within jBPM Business Central.

## Troubleshooting

If you encounter any issues during setup, consider the following tips:

- Ensure your Mac meets the system requirements for running jBPM.
- Verify that you’ve correctly entered the filesystem path when importing the project.
- If problems persist, consult the jBPM [documentation](https://www.jbpm.org/documentation.html) or reach out for support.

---

You’re now set up and ready to explore the Kibo Fulfillment Workflows in jBPM Business Central. Dive in, start automating, and enjoy working with this powerful business automation toolkit!