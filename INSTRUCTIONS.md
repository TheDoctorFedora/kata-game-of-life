# 🧩 Game of Life Kata

## 👥 Participants
- Two developers working in a pair (Driver/Navigator style)
- Switch roles every 10–15 minutes to keep collaboration balanced

---

## 🎯 Objective
Build a basic version of **Conway’s Game of Life** using **Test-Driven Development (TDD)**. Focus on:
- Clean code practices
- Effective pair communication
- Incremental design

---

## 📜 Game of Life Rules
Each cell in a grid is either **alive** or **dead**. With each tick (or generation), apply the following rules:
1. A **live** cell with fewer than two live neighbors **dies** (underpopulation).
2. A **live** cell with two or three live neighbors **lives on**.
3. A **live** cell with more than three live neighbors **dies** (overpopulation).
4. A **dead** cell with exactly three live neighbors **becomes alive** (reproduction).

---

## ⚠ Tips
- Start by writing a test for what we want to achieve
- Use small, focused commits
- Stick to the red-green-refactor TDD cycle
