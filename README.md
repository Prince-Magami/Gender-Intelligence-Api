# Profile Intelligence API

## Overview
This API builds enriched user profiles using multiple external APIs and stores them in a database.

## Features
- Multi API integration (Genderize, Agify, Nationalize)
- Data persistence with MongoDB
- Idempotency (no duplicate profiles)
- Filtering system
- Full CRUD support

## Endpoints

### POST /api/profiles
Create a profile

### GET /api/profiles/:id
Get single profile

### GET /api/profiles
Get all profiles (with filters)

### DELETE /api/profiles/:id
Delete profile
