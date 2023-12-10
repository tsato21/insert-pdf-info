---
layout: default
title: 'Google Apps Script for PDF Info Insertion'
---

## About this Project

This project involves a Google Apps Script that inserts PDF information into a Google Sheet. The script provides a custom menu in Google Sheets for the user to input a Google Drive folder URL. It then scans the folder for PDF files and inserts their names and URLs into the specified sheet.

- The script is manually triggered by the user through a custom menu in Google Sheets.
- The script scans a specified Google Drive folder for PDF files.
- The script inserts the name and URL of each PDF file into the Google Sheet.

## Prerequisites

- A Google account with access to Google Sheets and Google Drive.
- Basic understanding of Google Sheets and Google Apps Script.
- A Google Drive folder containing PDF files.

## Setup

1. **Open Your Google Sheet**: Access <a href="https://docs.google.com/spreadsheets/d/1z1i7ZYgkRRC0WS3xqS3CGh1GJ8iUQWKkcMwbVa3YU6Q/edit#gid=1971008536" target="_blank" rel="noopener noreferrer">Sample Google Sheet</a>.
2. Copy the Google Sheet to make your sheet.
3. **Conduct GAS Authorization**: Access `Initial Setting` Sheet and click the initial setting button. This enables you to go to the authorization page for Google Apps Script.

<div style="margin-left: 30px">
  <img src="assets/images/initial-setting.png" alt="Image of Initial Setting" width="200" height="100">
</div>

4. **Customize Constant Variables for Built-in Functions**: Navigate to the Apps Script page and adjust the constant variables to suit your needs.

## Usage

1. **Open the Google Sheet**: Open the Google Sheet where you want to insert the PDF information.

2. **Access the Custom Menu**: Click on the 'Custom Menu' that appears in the menu bar of the Google Sheet. Select 'Insert PDF info into Sheet'.

## Others

- **Folder URL Input**: A dialog box will appear asking for the Google Drive folder URL. Input the URL of the folder containing the PDF files you want to insert into the sheet.

- **Customization**: You can customize the scripts according to your specific preferences. For example, you can change the name of the sheet where the PDF information is inserted by modifying the `SHEET_NAME` constant.