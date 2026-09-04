# Tivo

[![Status: Under Development](https://img.shields.io/badge/Status-Under%20Development-orange.svg)](https://github.com/ElijahShepherd/Tivo)

Tivo is a free, open-source AI reminder app for Android phones and tablets. It allows users to quickly create and manage reminders using natural language and voice commands.

## About Tivo

Tivo uses AI to understand what the user wants to be reminded about, determine the correct time or schedule, and create the reminder automatically. The app is designed to be clean, smooth, and responsive.

Tivo uses an NVIDIA AI endpoint for AI processing and custom TTS for its voice responses.

Tivo is completely free and open source.

## Using Tivo

To create a reminder, simply say something beginning with "Tivo." Tivo supports one-time reminders, recurring reminders, specific times, and time intervals such as seconds, minutes, hours, and weeks.

Examples:

| Command                                                   |
| --------------------------------------------------------- |
| `Tivo, remind me in 10 minutes to call John.`             |
| `Tivo, remind me in 2 hours to check the oven.`           |
| `Tivo, remind me next week to pay the bill.`              |
| `Tivo, remind me tomorrow at 5 PM to take out the trash.` |
| `Tivo, remind me to drink water.`                         |
| `Tivo, remind me to check my email on a schedule.`        |

When no schedule is provided, Tivo automatically creates a reminder that repeats every 4 hours.

Tivo will also attempt to understand reminder requests that use different wording. If the request is not a reminder, is accidental, is not genuine, or cannot be properly understood, Tivo will cancel it.

```text
Reminder Canceled.
```

Canceled requests should be sent to a GitHub issue so the developer can review whether the request was a valid reminder.

Users can also ask Tivo about their reminders or delete a reminder.

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

Tivo can also provide a list of the user's reminders in a spoken response.

```text
Hey! You have [number of reminders]. [Name of first], [second], [and the rest of the reminders].
```

## Features

Tivo provides AI-powered reminder creation, automatic scheduling, recurring reminders, background processing, reminder editing, reminder deletion, reminder viewing, voice commands, and custom text-to-speech.

The AI may correct spelling and punctuation when naming a reminder, but it must never change the original idea or meaning of the user's request.

The app supports clean and responsive UI design and is intended to run smoothly on Android phones and tablets.

## Legal and More

Tivo is open source and completely free to use. However, the project is maintained exclusively by Elijah Shepherd.

Contributions, pull requests, and outside development are not accepted.

The project uses an NVIDIA AI endpoint and may require an internet connection for AI processing.

| Project       | Tivo            |
| ------------- | --------------- |
| Developer     | Elijah Shepherd |
| Maintainer    | Elijah Shepherd |
| Source        | Open source     |
| Cost          | Free            |
| Platform      | Android         |
| Contributions | Not accepted    |
| Pull Requests | Not accepted    |

See the repository license for the full legal terms.
