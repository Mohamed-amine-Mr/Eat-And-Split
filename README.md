# Friends Expense Splitter

## Description

This is a simple React application that helps users track and split expenses with their friends. Users can add friends, select them, and split bills based on their contributions.

## Features

- View a list of friends with their balances
- Add new friends
- Select a friend to split a bill with
- Enter bill details and calculate each person's share
- Update balances accordingly

## Technologies Used

- React.js
- useState Hook
- CSS (Styled with CSS Variables for consistency)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/friends-expense-splitter.git
   ```
2. Navigate to the project folder:
   ```sh
   cd friends-expense-splitter
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## Usage

1. Click the "Add Friend" button to add a new friend by entering their name and image URL.
2. Select a friend from the list to split a bill.
3. Enter the total bill amount and how much you have paid.
4. Select who is paying the bill.
5. Click "Split Bill" to update balances accordingly.

## File Structure

```
/src
  ├── components
  │   ├── Button.js
  │   ├── FriendsList.js
  │   ├── Friend.js
  │   ├── FormAddFriend.js
  │   ├── FormSplitBill.js
  ├── App.js
  ├── index.js
  ├── styles.css
```

## Contributing

Pull requests are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```sh
   git commit -m "Add a new feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, feel free to reach out:

- GitHub: [your-username](https://github.com/your-username)
- Email: your-email@example.com
