# Task Manager

Team Project – IT, Practical Assignment 1. Student ID: **73746**.

## Links

- Application: https://vistula-team-project-73746.github.io/vistula-task-manager/
- Repository: https://github.com/vistula-team-project-73746/vistula-task-manager
- Contributor page: https://vistula-team-project-73746.github.io/vistula-task-manager/contribution.html
- Contributor JSON: https://vistula-team-project-73746.github.io/vistula-task-manager/contribution.json

## Functionality

Display, create, edit, complete/uncomplete and delete tasks. Tasks are stored in Supabase PostgreSQL and survive page refreshes. Edit retrieves the current task by ID. The frontend uses fetch with Supabase REST GET, POST, PATCH and DELETE operations. Text is rendered using textContent.

## Setup

1. Create a separate free Supabase demonstration project with the Data API enabled.
2. Run `setup.sql` once in its SQL Editor. This creates the required table and public CRUD policies with RLS enabled.
3. Fill `supabaseUrl` and `supabasePublishableKey` in `config.json`. Use only the `sb_publishable_...` key. Keep `tableName` as `tasks`. Never commit database passwords or secret/service-role keys.
4. Publish GitHub Pages from the `main` branch, `/ (root)`.
5. Test the deployed site: add a test task, refresh, edit both fields, mark complete/incomplete, delete, refresh again. Check error messages with the network unavailable.

This is a public classroom demonstration. Visitors can read and change all tasks. Store test data only.

## Team collaboration

Partner: student **73279**, GitHub account **Vistula-team-project-73279**.

- Outgoing PR by student 73746, merged by the partner: https://github.com/Vistula-team-project-73279/vistula-task-manager/pull/1
- Incoming PR by student 73279, reviewed and merged by this repository owner: https://github.com/vistula-team-project-73746/vistula-task-manager/pull/1

The partner's incoming PR added contribution.html and contribution.json. On this website, Show Contributor fetches and displays **73279**. On the partner's website, the outgoing contribution displays **73746**.

Submit only the main application URL in Platon after checking the deployed pages.
