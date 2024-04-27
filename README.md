# polling-system-api


## API Endpoints

- `POST /questions/create`: Create a new question
- `POST /questions/:id/options/create`: Add an option to a question
- `DELETE /questions/:id`: Delete a question
- `DELETE /questions/:questionId/options/:optionId`: Delete an option from a question
- `PUT /options/:questionId/:optionId/add_vote`: Add a vote to an option
- `GET /questions/:id`: Get a question with it