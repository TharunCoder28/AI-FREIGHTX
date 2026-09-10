# FREIGHTX

Autonomous AI Freight Exception Manager

## Problem Statement

Freight disruptions are detected by existing logistics systems,
but resolving them often requires manual investigation,
comparison and coordination.

## Solution

FREIGHTX detects exceptions, analyzes their impact,
uses an AI reasoning layer to generate recovery strategies,
simulates their consequences, selects the lowest-impact
feasible action and executes the response.

## Key Innovation

What-If Decision Engine

Wait vs Reroute vs Reassign vs Split

## Architecture

[Architecture Diagram]

## Technology Stack

Frontend:
React + TypeScript

Backend:
Node.js / Python

API:
Gemini API

## Core Workflow

Detect
→ Understand
→ Simulate
→ Decide
→ Act
→ Verify

## Features

- Exception detection
- Impact analysis
- What-If simulation
- AI-assisted reasoning
- Decision validation
- Vehicle reassignment
- ETA update
- Driver notification
- Customer notification
- Autonomous replanning

## Demo Scenario

Vehicle V27 breaks down while carrying SHP-1042.

FREIGHTX evaluates:
Wait
Reroute
Reassign
Split

The system selects V31 based on the lowest
overall operational impact.

## Setup

# Create project
npm create vite@latest freightx -- --template react-ts
cd freightx

# Install dependencies
npm install

# UI + icons
npm install lucide-react

# Gemini API
npm install @google/genai

# Start development server
npm run dev

## Team Members

## Team Members

| Name | Registration Number | Program | Role |
|---|---|---|---|
| **Tharun R** | RA2612052010031 | M.Tech Data Science | Team Lead |
| **Vasanth S** | RA2612052010024 | M.Tech Data Science | Team Member |
| **J Sushanth** | RA2612052010025 | M.Tech Data Science | Team Member |
| **Syed Reahan** | RA2612052010020 | M.Tech Data Science | Team Member |

## Future Scope

Predictive disruption detection
Real-time GPS
Traffic and weather
TMS/ERP integration
Network-wide optimization
