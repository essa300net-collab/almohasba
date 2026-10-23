ZEED NET MANAGER - Prototype 0.1

This is a local-first web prototype of the intended Android accounting app.
Features:
- Arabic RTL interface
- Subscriber records
- Payment tracking
- Expense tracking
- Debt estimate (subscription fee minus recorded payments)
- Daily/monthly cash-flow report
- JSON backup/restore
- CSV export

Important limitations:
- Data is saved in this browser's localStorage on this device.
- Browser data can be cleared; use backups regularly.
- This package is NOT an APK and has not been packaged as a native Android app.
- Debt calculation is currently a simple single-fee estimate per subscriber, not recurring monthly billing.
- Test with sample data before using for real accounts.
