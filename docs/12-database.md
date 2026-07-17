# Database Architecture

## Overview

The database stores all user data, AI-generated content, learning progress, and workspace information.

---

## Database Choice

PostgreSQL

Reason:

- Reliable
- Scalable
- ACID Compliance

---

## Main Tables

Users

Organizations

Workspaces

Files

Chats

Messages

Notes

Summaries

Flashcards

Quizzes

Progress

Subscriptions

---

## Relationships

User

↓

Workspace

↓

Files

↓

AI

↓

Generated Content

---

## Indexes

- Email
- Workspace ID
- User ID
- File ID

---

## Future

- Read Replicas
- Database Partitioning
