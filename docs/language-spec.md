# Symbol Cast Language Specification
<!-- Detailed syntax and semantics of the Symbol Cast language -->
Symbol Cast is a gesture-based programming language that allows users to create programs by drawing symbols. These symbols represent various constructs such as loops, functions, and conditionals. The language supports both visual programming (gesture/symbol-based) and traditional text-based syntax.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Core Concepts](#core-concepts)
3. [Symbols and Syntax](#symbols-and-syntax)
   - [Classes](#classes)
   - [Functions](#functions)
   - [For and While Loops](#for-and-while-loops)
   - [Conditionals (If/Else)](#conditionals-ifelse)
   - [Variables](#variables)
4. [Examples](#examples)
5. [Integration with Other Languages](#integration-with-other-languages)
6. [Future Enhancements](#future-enhancements)

---

## Introduction

Symbol Cast is designed to make programming intuitive and accessible through visual gestures and symbolic representation. Users can either:
- Draw symbols on a canvas to represent constructs.
- Write equivalent Symbol Cast code directly.

The OS interprets these symbols into code in multiple target languages such as Python, JavaScript, or C++.

---

## Core Concepts

1. **Symbols as Code**:
   - Symbols act as building blocks for logic and computation.
   - Each symbol has a semantic meaning (e.g., loops, conditions).

2. **Dual Representation**:
   - **Symbolic Input**: Users draw gestures/symbols to represent logic.
   - **Textual Representation**: These symbols translate into textual Symbol Cast code.

3. **Dynamic Interactivity**:
   - The system provides real-time feedback and auto-completion based on drawn symbols.

---

## Symbols and Syntax

### Classes

#### **Symbol Representation**: 
A **rectangle** with the class name inside.

#### **Syntax**:
```plaintext
[ Class Symbol ] -> Translates to:

class ClassName:
    # Class body
