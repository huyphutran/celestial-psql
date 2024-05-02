# 💻 Project: Celestial Database

## Overview

The Celestial Database is a PostgreSQL database containing information about celestial objects such as stars, planets, moons, constellations, and galaxies. This database dump provides the schema structure and sample data for each table.

## Contents

1. [Introduction](#introduction)
2. [Project Goal](#project-goal)
3. [Database Schema](#database-schema)
4. [Installation](#installation)

## Introduction

The Celestial Database aims to organize astronomical data in a relational database format, making it accessible for research, education, and exploration purposes. It includes tables for storing information about various celestial objects, their attributes, and relationships.

## Project Goal

The goal of this project is to create a comprehensive and well-structured database that centralizes astronomical data. By providing a standardized schema and sample data, the Celestial Database aims to facilitate astronomical research, educational projects, and the development of astronomy-related applications.

## Database Schema

The database schema includes the following tables:

- `constellation`: Stores information about constellations, including name, region, number of stars, and visibility.
- `galaxy`: Contains data about galaxies, including name, type, size, presence of a black hole, and number of stars.
- `moon`: Stores details about moons, such as name, type, radius, tidal locking, and the planet they orbit.
- `planet`: Contains information about planets, including name, type, mass, atmosphere presence, and the star they orbit.
- `star`: Stores data about stars, including name, type, age, whether they are main sequence stars, and the galaxy they belong to.

## Installation

To set up the Celestial Database on your PostgreSQL server, follow these steps:

1. Download or clone this repository to your local machine.

2. Use the provided database dump file to create a new database in PostgreSQL. You can use the following command:

   ```bash
   psql -U <username> -d <database_name> -f celestial_database_dump.sql
