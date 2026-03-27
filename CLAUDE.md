# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Bike equipment management application - currently in early development stage.

**Core Features (planned):**
- Equipment library (purchase date, price tracking)
- Maintenance reminders (e.g., tire replacement)
- Used equipment valuation reference
- Equipment community (reviews, discussions)

**Tech Stack:**
- Backend: Java 21, Spring Boot, langchain4j
- Database: MySQL
- Cache: Redis
- Frontend: Taro

## Development Commands

```bash
# Build the project
mvn clean compile

# Run the application
mvn exec:java -Dexec.mainClass="org.yangsy.Main"

# Package
mvn clean package
```

## Project Status

This is a skeleton project with minimal setup:
- Java 21 configured in pom.xml
- Basic `src/main/java/org/yangsy/Main.java` entry point
- Spring Boot and langchain4j dependencies not yet added to pom.xml
