# Dining Philosopher

## Problem Statement

The Dining Philosophers is a classic concurrent programming challenge, first proposed as an exercise in an exam by Edsger Dijkstra in 1965. Imagine a group of philosophers, sitting at a round table. Each has a plate with food. For utensils, they have chopsticks - a single chopstick between each two plates (this setting correctly models the event budget of many Philosophy departments). In order to eat, each philosopher has to obtain both chopsticks adjacent to her. The concurrency challenge is, of course, mutual exclusivity: A chopstick may only be held by a single philosopher at any given moment, and so they have to either coordinate, or experience hunger-induced existential crisis
