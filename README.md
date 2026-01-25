# Freeze

![Always Green](ball.JPG)

[日本語](README.ja.md)

Freeze repository for the Always Green service.

## About This Repository

This repository records GitHub contributions when you use a freeze ticket.

With Always Green, you earn a "Freeze Ticket" after coding for 7 consecutive days. When you use a freeze ticket on busy days or when you're not feeling well, a commit is created in this repository, preserving your streak.

## How It Works

1. User uses a freeze ticket on Always Green
2. A date-based log file is created in this repository
3. The commit records a GitHub contribution
4. Your streak is maintained

## Log Structure

Freeze usage history is stored in the following format:

```
logs/
└── YYYY/
    └── MM/
        └── DD/
            └── freeze.md
```

Each file records the usernames of those who used a freeze on that day.

## Future Plans

Once this repository reaches 100 stars, we plan to develop iOS/Android widgets. You'll be able to check your streak status and remaining freeze tickets right from your home screen.

If you're interested, please give us a star!

## Links

- [Always Green](https://always-green.org/) - Main Service
- [Always Blue (Silicon Valley)](https://www.youtube.com/watch?v=ElJe5M54brI) - The inspiration for our name
