# Project Description

## Scenario

A healthcare organization maintains an allow list containing IP addresses permitted to access restricted patient information.

A separate remove list identifies employees whose access should be revoked. The objective is to automate the process of removing those IP addresses from the allow list and updating the file using Python.

## Objective

- Read the allow list from a text file.
- Compare entries against the remove list.
- Remove matching IP addresses.
- Save the revised allow list back to the file.
