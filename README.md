# 🚀 AI Workflow Studio - Enterprise AI Workflow Generator

> **Transform natural language business requirements into complete workflow automation solutions in seconds!**

[![Python Version](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/downloads/)
[![Node.js Version](https://img.shields.io/badge/node.js-18%2B-green.svg)](https://nodejs.org/)
[![React Version](https://img.shields.io/badge/react-18.2.0-61dafb.svg)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/fastapi-0.104.1-009688.svg)](https://fastapi.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Architecture](#-architecture)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Usage Guide](#-usage-guide)
- [API Documentation](#-api-documentation)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📋 Overview

**AI Workflow Studio** is an intelligent, AI-powered platform that converts natural language business requirements into professional workflow automation solutions. Built for learning and practice, this application bridges the gap between business ideas and technical implementation using state-of-the-art AI technologies.

### 🎯 What It Does

| Input | Output |
|-------|--------|
| "Create an employee onboarding workflow" | ✅ BPMN Diagram |
| "Design leave approval process" | ✅ Mermaid Flowchart |
| "Build API for ticket management" | ✅ OpenAPI Specification |
| "Generate SOP for customer support" | ✅ Professional SOP Document |
| "Automate invoice processing" | ✅ Automation Pipeline |

### 🌟 Why AI Workflow Studio?

- **⚡ 10x Faster** - Generate workflows in seconds instead of days
- **🧠 AI-Powered** - Uses Google Gemini AI for intelligent processing
- **🎨 Professional Output** - Industry-standard BPMN 2.0 and professional documentation
- **🚀 Zero Code** - No programming knowledge required
- **📤 Multi-Format Export** - BPMN, Mermaid, Markdown, OpenAPI, JSON

---

## ✨ Key Features

### 1. 🗣️ Natural Language to Workflow
- Input business requirements in plain English
- AI extracts steps, decisions, and flows
- Generates complete BPMN 2.0 diagrams

### 2. 📋 Automatic SOP Generator
- Creates detailed Standard Operating Procedures
- Includes roles, responsibilities, and KPIs
- Exports to Markdown and PDF

### 3. 🔌 API Blueprint Generator
- Generates REST API specifications
- Creates OpenAPI 3.0 documentation
- Ready-to-use Postman collections

### 4. 🎨 Visual Process Designer
- Interactive drag-and-drop interface
- Real-time diagram updates
- Export to PNG, SVG, PDF

### 5. 🤖 Automation Pipeline Builder
- Define triggers and actions
- Conditional logic
- Executable scripts generation

### 6. 📚 Template Library
- Pre-built workflow templates
- Industry-specific processes
- Best practices guides

---

## 🏗️ Architecture

### System Architecture Diagram

---

## 🛠️ Technology Stack

### Backend
```yaml
Language: Python 3.11+
Framework: FastAPI 0.104.1
Database: SQLite (Development)
ORM: SQLAlchemy 2.0+
AI/LLM: 
  - LangChain 0.0.340
  - LangGraph 0.0.20
  - Google Gemini AI
Validation: Pydantic 2.0+
Logging: Loguru 0.7+
Testing: Pytest 7.4+

git clone https://github.com/vishakha2121/ai-workflow-studio.git
cd ai-workflow-studio


# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env

# Edit .env and add your Gemini API Key
# GEMINI_API_KEY=your_api_key_here

# Open new terminal
cd frontend

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Edit .env if needed