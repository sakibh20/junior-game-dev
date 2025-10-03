---
template: SinglePost
title: Scriptable Object Custom Inspector
status: Published
date: 2025-04-15
featuredImage: https://ucarecdn.com/3631fe18-ea18-41f5-a3ed-119386495008/
excerpt: This tool addresses that by displaying only the necessary fields for
  the actual subclass type, streamlining the editing experience.

---
# Unity Custom Inspector for Hierarchical ScriptableObjects

This project showcases a **custom Unity Inspector** built to simplify editing complex **ScriptableObject hierarchies**. When dealing with deep inheritance trees and diverse data types, Unity’s default inspector becomes cluttered — showing fields that aren’t always relevant.

This tool addresses that by displaying **only the necessary fields** for the actual subclass type, streamlining the editing experience.

---

## Key Features

- **Context-aware field rendering**: Displays only the relevant fields for each asset’s specific subclass.
- **Supports deep inheritance trees**: Smoothly handles base and nested subclass fields.
- **Cleaner editor interface**: Eliminates noise in the inspector for better focus and usability.
- **Designed for modular architectures**: Perfect for ScriptableObject-driven systems.

---

## Project Context

This tool was part of a larger Unity project aimed at building scalable systems using ScriptableObjects, data-driven design, and custom tooling. It played a key role in improving designer experience and maintaining clean data structures.

---

## Technologies Used

- Unity Editor API
- Custom Inspectors (`Editor` / `EditorGUILayout`)
- ScriptableObject Inheritance
- Polymorphism

---

#### Gameplay Demo:
<iframe width="560" height="315" src="https://www.youtube.com/embed/o2PgCTTTR_A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
