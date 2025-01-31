---
title: 💸 Multi-Currency Group Expense Tracker Bot
date: 2024-12-28
description: This Telegram bot simplifies group expense tracking, bill splitting, and debt management across multiple currencies.
tag: telegram bot
author: Wai Yan
---

# Multi-Currency Group Expense Tracker Bot

This Telegram bot simplifies group expense tracking, bill splitting, and debt
management across multiple currencies. Whether you're planning a vacation,
sharing an apartment, or managing group activities, this bot helps keep
everyone's finances organized and transparent.

<div style="background: linear-gradient(135deg, #4F46E5 0%, #10B981 100%); padding: 1rem; border-radius: 12px; margin: 2rem 0; text-align: center; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); transition: transform 0.2s ease;">
  <a href="https://t.me/jarvisbellybot" style="color: white; text-decoration: none; font-weight: 600; display: flex; align-items: center; justify-content: center; gap: 1rem;">
    <span style="font-size: 1.5rem;">✨</span>
    <span>Try the Expense Tracker Bot</span>
    <span style="background: rgba(255, 255, 255, 0.15); padding: 0.375rem 1rem; border-radius: 9999px; font-size: 0.875rem; display: flex; align-items: center; gap: 0.5rem;">
      <span style="width: 6px; height: 6px; background: #4ade80; border-radius: 50%; animation: pulse 1.5s ease-in-out infinite;"></span>
      Live
      <style jsx>{`
        @keyframes pulse {
          0% { opacity: 0.6; }
          50% { opacity: 1; }
          100% { opacity: 0.6; }
        }
      `}</style>
    </span>
  </a>
</div>

## 🌟 Key Features

### Trip Management

Start by creating an expense tracking group for your trip or occasion. You can
set the default currency that works best for your group and manage member
access. The bot maintains a clear record of all participants and settings,
making it easy to keep track of who's involved in expense sharing.

<Image
  src="/images/budget/teletracker-9.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
  style="border-radius: 10px;"
/>

### Expense Tracking

Recording expenses is straightforward and flexible. When someone pays for the
group or lends money to another member, simply log the transaction. The bot
keeps track of all payments and debts, automatically calculating who owes what
to whom. It even includes smart debt simplification, automatically offsetting
mutual debts to minimize the number of transactions needed for settlement.

<Image
  src="/images/budget/teletracker-8.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
  style="border-radius: 10px;"
/>

### Bill Splitting

When you share a group expense, the bot can automatically split the bill among
selected members. Simply specify the total amount and who's involved, and the
bot will calculate each person's share and record it in the transaction history.
This feature is perfect for restaurant bills, shared purchases, or any group
expense that needs to be divided equally.

<Image
  src="/images/budget/teletracker-5.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
  style="border-radius: 10px;"
/>

### Reports and Analytics

Stay informed about your financial status within the group. The bot provides
comprehensive reports including personal debt summaries, group-wide debt
rankings, and detailed transaction histories. You can compare transactions
between any two members to resolve discrepancies and export complete transaction
logs as CSV files for your records. A web dashboard is also available for
viewing the transaction history.

<Image
  src="/images/budget/teletracker-6.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
  style="border-radius: 10px;"
/>

<Image
  src="/images/budget/teletracker-10.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
  style="border-radius: 10px;"
/>

Web dashboard for viewing the transaction history.

## 📱 Available Commands

| Command       | Description                              | Example                                       |
| ------------- | ---------------------------------------- | --------------------------------------------- |
| `/newtrip`    | Initialize a new trip/group              | `/newtrip VacationJune USD john,jane,michael` |
| `/tripinfo`   | View current trip settings               | `/tripinfo`                                   |
| `/adduser`    | Add new members                          | `/adduser john`                               |
| `/removeuser` | Remove a member                          | `/removeuser john`                            |
| `/new`        | Record a transaction                     | `/new john paid jane 100 for lunch`           |
| `/split`      | Split a bill among members               | `/split dinner john 150 jane michael liv`     |
| `/ranking`    | View debt rankings                       | `/ranking`                                    |
| `/debts`      | View all current debts                   | `/debts`                                      |
| `/me`         | View personal transaction history        | `/me john`                                    |
| `/compare`    | Compare transactions between two members | `/compare john jane`                          |
| `/logs`       | Export transaction history               | `/logs`                                       |

## 💡 Usage Examples

### Recording a Payment

When John pays for Jane's lunch, simply record it with the command
`/new john paid jane 100 for lunch`. This logs that John paid $100 for Jane's
lunch in the group's transaction history.

### Recording a Debt

If John needs to record that he owes Jane money for tickets, use
`/new john owes jane 50 for tickets`. This creates a debt record showing John
owes Jane $50.

### Splitting a Bill

For group expenses like dinner, use the split command. For example,
`/split dinner john 150 jane michael liv` will divide a $150 dinner bill paid by
John equally between Jane, Michael, and Liv.

### Viewing Personal Status

To check your financial status in the group, use the me command. For instance,
`/me john` shows all of John's current debts and credits within the group.

## 🔐 Privacy & Security

Your financial data's privacy is a top priority. The bot operates exclusively in
group chats, and only registered members can participate in transactions. All
transaction history is securely stored and accessible only to group members,
ensuring your financial information stays private.

## ⚠️ Important Notes

Double-checking transaction amounts before confirming is essential for accuracy.
Always use correct usernames when recording transactions, and ensure all members
are added to the trip before recording their expenses. The bot includes
automatic debt simplification to reduce the complexity of settlements between
members.

## 🤝 Best Practices

Maintaining accurate records requires prompt recording of expenses as they
occur. Regular checks of the debt rankings help everyone stay informed of their
financial status. When questions arise, use the compare feature to review
transactions between specific members. It's recommended to export logs
periodically for backup purposes. Before starting a new trip or group, ensure
all members agree on the default currency to avoid confusion.

