# Tivo

Tivo is a free, open-source AI reminder app for Android phones and tablets. It allows users to quickly create and manage reminders using natural language and voice commands.

## About Tivo

Tivo uses AI to understand what the user wants to be reminded about, determine the appropriate time or schedule, and create the reminder automatically. The app is designed to provide a clean, smooth, and responsive experience.

Tivo uses an NVIDIA AI endpoint for AI processing and custom TTS for voice responses.

Tivo is completely free and open source.

When Tivo is triggered, a listening card appears at the bottom of the device with a subtle pink color to indicate the listening state. While the request is being processed, a loading animation is displayed. Once processing is complete, Tivo provides a confirmation message.

## Using Tivo

To create a reminder, simply say something beginning with **"Tivo."**

Tivo supports one-time reminders, recurring reminders, specific times, and time intervals including seconds, minutes, hours, and weeks.

| Command                                                   |
| --------------------------------------------------------- |
| `Tivo, remind me in 10 minutes to call John.`             |
| `Tivo, remind me in 2 hours to check the oven.`           |
| `Tivo, remind me next week to pay the bill.`              |
| `Tivo, remind me tomorrow at 5 PM to take out the trash.` |
| `Tivo, remind me to drink water.`                         |
| `Tivo, remind me to check my email on a schedule.`        |

When no schedule is provided, Tivo automatically creates a reminder that repeats every 4 hours.

Tivo will also attempt to understand reminder requests phrased in different ways. If a request is not a reminder, is accidental, is not genuine, or cannot be properly understood, Tivo cancels the request.

```text
Reminder Canceled.
```

Canceled requests should be sent to a GitHub issue so the developer can review whether the request was a valid reminder.

Users can also ask Tivo about their reminders or delete existing reminders.

| Command                               |
| ------------------------------------- |
| `Tivo, what are my reminders?`        |
| `Tivo, delete my call John reminder.` |

Tivo responds using custom TTS.

| Situation          | Response                                    |
| ------------------ | ------------------------------------------- |
| Reminder created   | `Okay! I have set your reminder.`           |
| Reminder deleted   | `Done. I deleted the reminder.`             |
| Reminder not found | `I did not find the reminder. Check again.` |

Tivo can also provide a spoken list of the user's reminders.

```text
Hey! You have [number of reminders]. [Name of first], [second], [and the rest of the reminders].
```

## Features

| Feature                   | Description                                                                                                                                                                                            |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Listening Card**        | Appears at the bottom of the device with a subtle pink color indicating the listening state. A loading animation is displayed while the request is being processed, followed by a completion response. |
| **AI Processing**         | Uses an NVIDIA AI endpoint to understand reminder requests and determine the appropriate time or schedule.                                                                                             |
| **Custom TTS**            | Provides voice responses for user interactions.                                                                                                                                                        |
| **Voice Commands**        | Supports creating and managing reminders through natural language voice commands.                                                                                                                      |
| **Recurring Reminders**   | Automatically creates reminders that repeat every 4 hours when no schedule is provided.                                                                                                                |
| **Reminder Editing**      | Allows users to modify existing reminders.                                                                                                                                                             |
| **Reminder Deletion**     | Allows users to delete existing reminders.                                                                                                                                                             |
| **Reminder Viewing**      | Allows users to view their current reminders.                                                                                                                                                          |
| **Background Processing** | Processes and manages reminders in the background.                                                                                                                                                     |
| **Automatic Scheduling**  | Determines reminder timing and scheduling from natural language requests.                                                                                                                              |
| **Platform**              | Designed to run smoothly on Android phones and tablets.                                                                                                                                                |

The AI may correct spelling and punctuation when naming a reminder, but it must never change the original idea or meaning of the user's request.

## Legal and More

Tivo is open source and completely free to use. However, the project is maintained exclusively by Elijah Shepherd.

Contributions, pull requests, and outside development are not accepted.

The project uses an NVIDIA AI endpoint and may require an internet connection for AI processing.

| Project           | Tivo            |
| ----------------- | --------------- |
| **Developer**     | Elijah Shepherd |
| **Maintainer**    | Elijah Shepherd |
| **Source**        | Open source     |
| **Cost**          | Free            |
| **Platform**      | Android         |
| **Contributions** | Not accepted    |
| **Pull Requests** | Not accepted    |

See the repository license for the full legal terms.
