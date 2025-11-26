# M-Pesa Simulator

A functional M-Pesa mobile money simulator built with vanilla HTML, CSS, and JavaScript. This simulator allows you to practice common M-Pesa transactions including sending money, depositing, and viewing transaction history.

## Features

✨ **Core Features:**
- 💰 View Account Balance
- 📤 Send Money to other users
- 💵 Deposit Money
- 📋 Transaction History
- 💬 Message Center
- ⚙️ Settings (Phone Number & Initial Balance)

## How to Use

1. **First Time Setup:**
   - Click the ⚙️ settings button
   - Enter your phone number
   - Set an initial balance
   - Click Save Settings

2. **Send Money:**
   - Navigate to "Send Money" tab
   - Enter recipient's phone number
   - Enter amount in KES
   - Add optional message
   - Click "Send Money"

3. **Deposit Money:**
   - Click "Deposit" button on home screen
   - Enter amount to add to your account
   - Transaction will appear in history

4. **View History:**
   - Check "Recent Transactions" on home screen
   - All sent and received money is tracked
   - View details with timestamps

## Live Demo

🌐 **Visit:** [M-Pesa Simulator](https://joyfulbluegoose.github.io/mpesa-sim)

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Modern responsive design
- **JavaScript (ES6)** - Interactive functionality
- **LocalStorage** - Data persistence

## Features Breakdown

### Home Tab
- Display current balance
- Quick action buttons
- Recent transaction list
- Auto-saves all data to browser localStorage

### Send Money Tab
- Phone number validation
- Amount input with decimal support
- Optional message field
- Balance validation before sending

### Messages Tab
- View all transaction confirmations
- Timestamped messages
- Transaction status tracking

### Settings
- Set custom phone number
- Initialize account balance
- All data persists on page reload

## Data Storage

All data is stored locally in your browser using localStorage. No data is sent to any server. Clear your browser data to reset the simulator.

## Testing Scenarios

**Test these scenarios:**
- ✅ Try sending with insufficient balance
- ✅ Try invalid phone numbers
- ✅ Send money and check transaction history
- ✅ Deposit multiple times and watch balance grow
- ✅ Change settings and verify persistence
- ✅ Check messages for transaction confirmations

## Browser Compatibility

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## Installation

No installation needed! This is a completely browser-based application.

```bash
# Clone the repository
git clone https://github.com/JoyfulBlueGoose/mpesa-sim.git

# Navigate to folder
cd mpesa-sim

# Open in browser (double-click index.html or use a local server)
python -m http.server 8000
# Then visit http://localhost:8000
```

## License

This project is open source and available under the MIT License.

## Author

Created by JoyfulBlueGoose

---

**Note:** This is a simulator for educational and practice purposes only. It does not connect to any real M-Pesa system.
