# Quick Start Guide: jBPM Business Central

Welcome to the jBPM Business Central Quick Start Guide for reviewing or working with Kibo Fulfillment related business assets. This document will help you set up a local instance of jBPM Business Central, a powerful toolkit for building business applications to automate business processes and decisions. This guide will walk you through the steps needed to get jBPM running on your system, as well as downloading and importing this project.

## Prerequisites

- A Mac computer
- Basic understanding of terminal commands
- Internet access to download necessary files

## Step 1: Download jBPM

1. Visit the [jBPM website](https://www.jbpm.org/).
2. Download the latest stable version of jBPM (7.74.1.Final) for Mac.
3. Once the download is complete, unzip the downloaded file.

## Step 2: Start jBPM Business Central

1. Open your terminal.
2. Navigate to the unzipped jBPM folder.
3. Run the following command to start the jBPM server:
    ```bash
    jbpm-server/bin/standalone.sh
    ```
4. Wait for the server to start. Once it's running, open your web browser and go to:
    ```
    http://localhost:8080/business-central
    ```

## Step 3: Log In to Business Central

- **Username:** wbadmin
- **Password:** wbadmin

After logging in, you will have access to the jBPM Business Central environment where you can create, modify, and manage business processes.

## Step 4: Clone the Kibo Fulfillment Workflows Project

1. Open a new terminal window.
2. Navigate to the directory where you want to clone the project.
3. Run the following git command:
    ```bash
    git clone https://github.com/KiboSoftware/kibo-fulfillment-workflows.git
    ```

This command will download the Kibo Fulfillment Workflows project to your local machine.

## Step 5: Import the Project into Business Central

1. In Business Central, navigate to **Menu > Design > Projects**.
2. Click on the **Add Project** button (located on the right side of the screen).
3. Select **Import Project** from the dropdown menu.
4. In the **Repository URL** field, enter the filesystem location of the cloned repository. The format should be:
    ```
    file:///{filesystem_location_of_cloned_repository}
    ```
    - For example:
    ```
    file:///Users/your_username/projects/kibo-fulfillment-workflows
    ```
5. Click **Import**.
6. Select the project that appears to confirm the import.
7. Click **Ok**.

## Step 6: Review and Modify Business Assets

Once the project is imported, you can start working on it. Explore the project to review and modify business assets such as processes, forms, rules, and decision tables.

## Troubleshooting

If you encounter any issues during setup, feel free to reach out for assistance. The jBPM environment might be resource-intensive, so ensure your system meets the basic requirements.

---

That's it! You're now ready to explore and work with jBPM Business Central.