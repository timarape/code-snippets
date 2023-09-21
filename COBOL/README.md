# COBOL Programming Language

![COBOL Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/COBOL_-_Common_Business_Oriented_Language.svg/220px-COBOL_-_Common_Business_Oriented_Language.svg.png)

Welcome to the COBOL Programming Language README! This document serves as an introduction and resource guide for those interested in learning and working with COBOL.

## Table of Contents
- [What is COBOL?](#what-is-cobol)
- [Getting Started](#getting-started)
- [Basic Syntax](#basic-syntax)
- [Data Types](#data-types)
- [Control Structures](#control-structures)
- [File Handling](#file-handling)
- [COBOL in Business](#cobol-in-business)
- [Resources](#resources)

## What is COBOL?
COBOL, which stands for Common Business-Oriented Language, is a programming language developed in the late 1950s for business data processing. It is known for its readability and is still widely used in financial, government, and administrative systems worldwide.

## Getting Started
To start programming in COBOL, you'll need the following:
1. **Development Environment**: Install a COBOL compiler or development environment like GNU COBOL (OpenCOBOL) or Micro Focus Visual COBOL.
2. **Text Editor or IDE**: Choose a text editor or integrated development environment suitable for COBOL programming.
3. **COBOL Documentation**: Familiarize yourself with COBOL syntax, rules, and best practices.

## Basic Syntax
COBOL has a unique syntax designed for business-oriented applications. Here's a simple "Hello, World!" program in COBOL:

```cobol
       IDENTIFICATION DIVISION.
       PROGRAM-ID. HelloWorld.
       PROCEDURE DIVISION.
           DISPLAY 'Hello, World!'.
           STOP RUN.
