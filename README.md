# Webhook Module – LINE Official Account

## Overview

| Item | Description |
|-----|-------------|
| Module | Webhook Service |
| Project | Kamphaeng Phet Community Hospital LINE OA Platform |
| Function | Process events from LINE Messaging API |
| Role | Integration layer with backend services |

---

## Architecture Role

| Layer | Responsibility |
|------|---------------|
| Interface | Receive LINE webhook requests |
| Processing | Validate and dispatch events |
| Integration | Communicate with backend APIs |

---

## Event Flow

| Step | Description |
|------|-------------|
| 1 | LINE sends event to webhook endpoint |
| 2 | Signature validation is performed |
| 3 | Event is routed to handler |
| 4 | Backend logic is executed |
| 5 | Response is sent via LINE API |

---

## Core Components

| Component | Description |
|----------|-------------|
| Webhook Controller | Entry point for events |
| Event Dispatcher | Routes events |
| Event Handlers | Business logic |
| LINE API Client | Message delivery |

---

## Configuration

| Variable | Purpose |
|----------|---------|
| LINE_CHANNEL_SECRET | Request validation |
| LINE_CHANNEL_TOKEN | LINE API access |
| WEBHOOK_PATH | Public endpoint |
| BACKEND_API_URL | Backend integration |

---

## Deployment

| Item | Requirement |
|------|-------------|
| Protocol | HTTPS |
| Environment | Server or cloud |
| Usage | Official use only |

---

## Ownership

| Item | Detail |
|------|--------|
| Organization | Kamphaeng Phet Community Municipal Hospital |
