# Command Line for the Win

## Project Overview

This project involves completing various tasks and taking screenshots at different levels. The completion of each task is indicated by the turning of the task name to green.

## Screenshots

Screenshots of the completed levels can be found in the directory `/root/alx-system_engineering-devops/command_line_for_the_win/`.

## SFTP File Transfer

To transfer the screenshots to the sandbox environment, follow these steps:

1. Open a terminal or command prompt on your local machine.

2. Use the SFTP command-line tool to establish a connection to the sandbox environment. Replace `<hostname>`, `<username>`, and `<password>` with the provided information:

    ```bash
    sftp <username>@<hostname>
    ```

3. Navigate to the directory where you want to upload the screenshots:

    ```bash
    cd /path/to/sandbox/directory
    ```

4. Use the SFTP `put` command to upload the screenshots from your local machine to the sandbox environment. Replace `<local_screenshot>` with the actual filename:

    ```bash
    put /path/to/local/screenshot.png
    ```

    Repeat this step for each screenshot.

5. Confirm that the screenshots have been successfully transferred by checking the sandbox directory.

6. Once the screenshots are transferred, push the screenshots to GitHub:

    ```bash
    git add .
    git commit -m "Add screenshots for completed levels"
    git push origin main
    ```

## Manual QA Review

Request a review for this project from a peer. If no peers have reviewed, request a review from a TA or staff member.

