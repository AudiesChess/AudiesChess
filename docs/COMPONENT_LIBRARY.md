# AudiesChess Component Library

Version: 0.1
Status: Core

---

# Philosophy

Build reusable components.

Avoid duplicated UI.

Every component should have a single responsibility.

Prefer composition over duplication.

---

# Layout Components

## AppLayout

Purpose

Main application layout after login.

Contains

- Navbar
- Sidebar
- Main Content

---

## Navbar

Purpose

Global navigation.

Contains

- Logo
- Navigation
- Search
- Notifications
- Profile

---

## Sidebar

Purpose

Quick navigation.

Contains

- Home
- Play
- Learn
- AI
- Community

---

## Footer

Purpose

Footer for public pages.

---

# Navigation Components

## NavItem

Single navigation item.

---

## Breadcrumb

Current page path.

---

## SearchBar

Global search.

---

# Button Components

## PrimaryButton

Main action.

---

## SecondaryButton

Alternative action.

---

## IconButton

Icon only.

---

## GhostButton

Minimal action.

---

# Card Components

## Card

Base reusable card.

---

## MissionCard

Today's mission.

---

## ProgressCard

Player progress.

---

## AIRecommendationCard

AI recommendations.

---

## CourseCard

Learning content.

---

## GameCard

Recent games.

---

## EventCard

Tournament and events.

---

# Chess Components

## ChessBoard

Main board.

---

## ChessClock

Game timer.

---

## MoveList

Move history.

---

## EvaluationBar

Engine evaluation.

---

## CapturedPieces

Captured material.

---

## GameControls

Resign

Draw

Flip Board

Settings

---

# AI Components

## AICoachCard

Daily coaching.

---

## AIInsight

Weakness report.

---

## TrainingPlan

Recommended training.

---

## AIChat

Future feature.

---

# Learning Components

## LessonCard

---

## OpeningCard

---

## PuzzleCard

---

## EndgameCard

---

## ProgressBar

---

# Community Components

## FriendCard

---

## ClubCard

---

## LeaderboardCard

---

## TournamentCard

---

# Profile Components

## Avatar

---

## RatingBadge

---

## AchievementBadge

---

## StatisticsCard

---

# Form Components

## Input

---

## Select

---

## Checkbox

---

## Switch

---

## Modal

---

## Dialog

---

## Toast

---

## Tooltip

---

# Loading Components

## Spinner

---

## Skeleton

---

## EmptyState

---

## ErrorState

---

# Component Rules

Every component should:

- Be reusable
- Have one responsibility
- Support dark mode
- Be responsive
- Be accessible
- Be easy to extend

Avoid creating page-specific components whenever possible.

Start with generic components first.
