# n8n API Automation

## Overview
This project demonstrates an API automation workflow built in n8n.

## Workflow
1. Schedule Trigger starts the workflow.
2. HTTP Request fetches posts from JSONPlaceholder API.
3. JavaScript filters and selects the latest 5 posts.
4. HTTP Request fetches user details for each selected post.
5. IF node checks the user ID condition.
6. Email node sends the resulting user details.

## APIs Used
- JSONPlaceholder Posts API
- JSONPlaceholder Users API

## Tools
- n8n
- JavaScript
- REST API
- SMTP Email

## Workflow File
`Task2_Workflow_VikasVerma.json`
