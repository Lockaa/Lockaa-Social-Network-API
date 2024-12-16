# Social Network API

## Installation

Clone the repository:

```sh
git clone https://github.com/Lockaa/Lockaa-Social-Network-API
```

Install the required dependencies:

```sh
npm install
```

Run the project in your local browser:

```sh
npm start
```


## Usage

Use your browser or an app like [Insomnia](https://insomnia.rest/) to test the REST API.

## Endpoints

**User**
- Get all users:        `GET /api/users`
- Create a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:userId`
- Update a user:        `PUT /api/users/:userId`
- Delete a user:        `DELETE /api/users/:userId`
- Add a friend:         `PUT /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Thought**
- Get all thoughts:     `GET /api/thoughts`
- Create a thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:thoughtId`
- Update a thought:     `PUT /api/thoughts/:thoughtId`
- Delete a thought:     `DELETE /api/thoughts/:thoughtId`

**Reaction**
- Add a reaction:       `PUT /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions`

## Meta

Distributed under the MIT license. See ``LICENSE`` for more information.

## Contributing

1. Fork it (<https://github.com/Lockaa/Lockaa-Social-Network-API/fork>)
2. Create your feature branch (`git checkout -b feature/featureName`)
3. Commit your changes (`git commit -am 'Add some featureName'`)
4. Push to the branch (`git push origin feature/featureName`)
5. Create a new Pull Request

