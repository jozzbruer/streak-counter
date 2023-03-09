# `@jquince/streak-counter` - A streak counter to cheers users progress

This is a streak counter - Inspired by Duolingo- But for browser and use `localStorage`

## Install

```shell
 npm install @jquince/streak-counter
```

```shell
 yarn add @jquince/streak-counter
```

### Usage

```typescript
import { streakCounter } from '@jquince/streak-counter';

const today = new Date();

const streak = streakCounter(localStorage, today);

/**
 *  streak returns an object
 *
 * {
 *  currentCount: 1,
 *  lastLoginDate: '11/11/11
 *  startDate: '09/11/10'
 * }
 * /
```
