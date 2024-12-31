Project Overview
In this project, you will use starter code to develop and deploy a simple Task List application using AWS Lambda and Serverless framework. This application will allow users to create/remove/update/get task list items. Each task list item contains the following fields:

todoId (string) - a unique id for a task list item
createdAt (string) - date and time when a task list item was created
name (string) - name of a task list item (e.g. "Change a light bulb")
dueDate (string) - date and time by which a task list item should be completed
done (boolean) - true if a task list item was completed, false otherwise
attachmentUrl (string) (optional) - a URL pointing to an image attached to a task list item
You might also store an id of a user who created a task list item. Each task list item can optionally have an attachment image. Each user only has access to the task list items that they have created.